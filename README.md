# sql_challenge
 Module 9 challenge submission

In this project the first major task is a research project about people whom the company employed during the 1980s and 1990s. The employee database from that period are six CSV files.

Following three steps are peformed in this project:

## 1. Data Modelling

    The table schema is created by designing the ERD diagram using [title](https://app.quickdatabasediagrams.com/#/)

## 2. Data Engineering

    The following tables have been designed to hold the data from the CSV files:

    1. departments
    2. titles
    3. employees
    4. dept_manager
    5. dept_emp
    6. salaries

## 3. Data Analysis

    The following analysis was carried out in PostgreSQL:

        List the employee number, last name, first name, sex, and salary of each employee.

        List the first name, last name, and hire date for the employees who were hired in 1986.

        List the manager of each department along with their department number, department name, employee number, last name, and first name.

        List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

        List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

        List each employee in the Sales department, including their employee number, last name, and first name.

        List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

        List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).