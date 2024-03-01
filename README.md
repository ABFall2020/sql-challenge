# Employee Database
- Module 9 Challenge
  
## Challenge Instructions
This project utilizes Data Engineering and Data Analysis to build a SQL database of employees of a corporation called Pewlett Hackard from the 1980s and 1990s. There are six CSV files holding the data of employees. The SQL tables were designed and the data in the CSVs were successfully imported into a SQL database. 

## This project is divided into three parts: 

### Data Modeling:
Sketch an Enitity Relationship Diagram based on the provided CSV files in the data folder.
## - This is shown in the employee-ERD.jpg file in the EmployeeSQL folder

### Data Engineering:
Using the provided information to create a table schema for each of the six CSV files and specify data types, primary keys, foreign keys, and other constraints.
  - For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.
  - Be sure to create tables in the correct order to handle foreign keys.
    
Import each CSV file into the corresponding SQL table and make sure to import the data in the same order that the tables were created.
## - These are performed in the schema.sql file in the EmployeeSQL folder.
  
### Data Analysis:
- List the employee number, last name, first name, sex, and salary of each employee.
- List the first name, last name, and hire date for the employees who were hired in 1986.
- List the manager of each department along with their department number, department name, employee number, last name, and first name.
- List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
- List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
- List each employee in the Sales department, including their employee number, last name, and first name.
- List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
- List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

## - These are performed in the query.sql file in the EmployeeSQL folder.
