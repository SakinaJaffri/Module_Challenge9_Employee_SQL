# Employee Database Challenge (SQL)

![Employee Database](https://github.com/SakinaJaffri/Module_Challenge9_Employee_SQL/assets/146900226/5c1a3f18-d3f1-48d6-847e-4dd4be7c740a)

## Overview

This project involves designing, implementing, and analyzing an **employee database** using SQL. It includes three major components: **data modeling**, **data engineering**, and **data analysis**. The goal is to create a functional database for employee data, perform SQL queries to retrieve information, and extract meaningful insights.

## Project Workflow

### 1. Data Modeling
- **Entity Relationship Diagram (ERD)**: 
  - Sketched an ERD based on the provided CSV files to understand relationships between tables.
  - Used QuickDBD or similar tools to create the ERD.

### 2. Data Engineering
- **Table Schema Creation**:
  - Defined table schemas for six CSV files (`employees.csv`, `departments.csv`, `dept_emp.csv`, `dept_manager.csv`, `titles.csv`, `salaries.csv`).
  - Specified data types, primary keys, foreign keys, and constraints to ensure database integrity.
  - Imported data from CSV files into SQL tables in the correct order.

### 3. Data Analysis
- Executed several SQL queries to analyze the employee data:

  - **Employee Details**: Retrieved employee number, last name, first name, sex, and salary.
  - **Employees Hired in 1986**: Listed employees hired in the year 1986.
  - **Department Managers**: Displayed the manager details for each department.
  - **Employee Departments**: Showed department assignments for each employee.
  - **Employees Named Hercules**: Filtered employees with the first name "Hercules" and last names starting with "B."
  - **Sales Department Employees**: Retrieved details of employees working in the Sales department.
  - **Sales and Development Employees**: Listed employees from both Sales and Development departments.
  - **Last Name Frequencies**: Displayed the frequency of last names in the employee database.

## Technologies Used
- **SQL**: For database creation, data manipulation, and query execution.
- **PostgreSQL** or **MySQL**: Preferred database management systems.
- **QuickDBD**: For creating the ERD.

## How to Use
1. Clone the repository to your local machine.
2. Set up a local or remote database (PostgreSQL or MySQL).
3. Use the provided SQL scripts to create the database tables and import data from the CSV files.
4. Execute the SQL queries to perform the data analysis tasks.

## Entity Relationship Diagram (ERD)
The ERD represents the relationships between the various entities (employees, departments, managers, salaries, etc.) in the database. It is essential for understanding the database structure before running queries.

## Conclusion
This project demonstrates the process of designing and implementing a relational database for employee records, along with performing insightful data analysis using SQL queries. It highlights the importance of data modeling, schema design, and efficient querying for extracting relevant information.

## Contributors
- **Sakina Jaffri** - Project Developer
