# HR-database
SQL project on HR database (MYSQL)
The HR database project involves creating a database to store information about employees, departments, salaries, job titles, and department managers in a company. The database contains six tables: employees, departments, dept_emp, dept_manager, salaries, and titles.

The employees table stores basic information about all employees, including their personal details and date of hire. The departments table stores information about all departments in the company, including their department number and name. The dept_emp table links employees to the departments to which they belong and the time period for which they were in that department. The dept_manager table stores information about the managers of each department and the time period for which they held that position. The salaries table stores information about the salary history of each employee, including the amount of their salary and the time period for which they received that salary. Finally, the titles table stores information about the job titles held by each employee and the time period for which they held each title.

The project involves creating several queries and modifications to the database, including updating the hire date and birth date of employees to a different year range, calculating the number of years each department manager worked in their position, finding the number of employees under each manager, and adding new columns to some of the tables.

The HR database project is useful for tracking employee information and job history in a company and can be used for generating reports and analyzing employee data.

Database Description: 
employees table:
Columns: emp_no (primary key), birth_date, first_name, last_name, gender, and hire_date
Contains information about all employees in the company, including their personal details and date of hire.

departments table:
Columns: dept_no (primary key) and dept_name
Contains information about all departments in the company, including their department number and name.

dept_emp table:
Columns: emp_no, dept_no, from_date, and to_date
Contains information about the department to which an employee belongs and the time period for which the employee was in that department.

dept_manager table:
Columns: dept_no, emp_no, from_date, and to_date
Contains information about the manager of each department and the time period for which they held that position.

salaries table:
Columns: emp_no, salary, from_date, and to_date
Contains information about the salary history of each employee, including the amount of their salary and the time period for which they received that salary.

titles table:
Columns: emp_no, title, from_date, and to_date
Contains information about the job titles held by each employee and the time period for which they held each title.
