# PostgreSQL Script

### Background 
Acting as a Data Engineer I developed SQL queries to research and analyze employee data from six CSV files. The project is broken into 3 parts: data modeling, data engineering, and data analysis.

#### Data Modeling

I developed an ERD (Entity Relationship Diagram) for the project

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/ERD.png)

#### Data Engineering

I ensured that all essential columns are defined for each table and are assigned the appropriate data types. I set primary keys for each table and establishing accurate references between related tables contribute to a well-structured database. The integration of foreign keys is crucial for establishing correct relationshipes between tables. I applied the NOT NULL condition to necessary columns to ensure data integrity. Additionally, defining value lengths for columns adds another layer of accuracy, collectively forming the foundation of effective data management.

#### Data Analysis
I developed 8 queries to analyze the data for this project


##### _Employee number, last name, first name, sex, and salary of each employee_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/employee_list(1).png)


##### _First name, last name, and hire date for the employees who were hired in 1986_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/1986_hire_date(2).png)


##### _Manager of each department along with their department number, department name, employee number, last name, and first name_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/dept_manager(3).png)


##### _Department number for each employee along with that employee’s employee number, last name, first name, and department name_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/deptid_empno(4).png)


##### _First name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/hercules(5).png)


##### _Employee in the Sales department, including their employee number, last name, and first name_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/sales_team(6).png)


##### _Employee in the Sales & Development departments, including their employee number, last name, first name, and department name_

![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/sales_and_development_dept(7).png)


_Frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name)_
![Alt Text](https://github.com/peatk/SQL-Challenge/blob/main/EmployeeSQL/data/last_name_totals(8).png)


