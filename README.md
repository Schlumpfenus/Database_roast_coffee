# MS-SQL and database development

## This repository in general:
- As part of my extension studies in Data Analytics I took part in the class mentioned above
- The classes are certified by the AZAV standard in order to meet the requirements of the 'Agentur für Arbeit'

## What you can find in this repository:
- Here you can find the code for the final project which was necessary to pass the class MS-SQL and database development
- Requirements of the final project:

### Design, implement, and code a relational Database

#### Task

- Avoid redundancies and inconsistencies
- The database should manage dynamic data (not only static data)
- Implement business logic (see below for procedures and triggers)
- For an “excellent” grade: include at least 10 tables
- Create primary indexes and, where needed, secondary non-clustered indexes
- Establish relationships between tables
- Include at least one many-to-many (m:n) relationship
- Define default values and constraints
- Create an entity-relationship-model (ERM) of the database
- Save CREATE scripts, including:
  - CREATE DATABASE
  - Individual scripts for:
          
              CREATE TABLE
          
              CREATE NONCLUSTERED INDEX
          
              ADD CONSTRAINT FOREIGN KEY
          
              ADD CONSTRAINT CHECK
#### Data:

- Include enough records to test the business logic, but avoid excessive data

#### Views:

- Create a SELECT view across multiple tables, using INNER JOINs
- Create a SELECT view with GROUP BY, SUM, or COUNT, including HAVING
- For an “excellent” grade: create a view across multiple tables using LEFT, RIGHT, FULL OUTER JOIN, or SELF JOIN
- Save all scripts

#### Stored Functions:
- Create a scalar function
- Create a table-valued function
- Create test scripts
- Save all scripts.

#### Stored Procedures:

- Develop a stored procedure with parameters
- The procedure should implement business logic
- Validate input parameters and modify data in tables
- For an “excellent” grade:
  - Use custom functions within the procedure
  - Include OUTPUT parameters for error messages or other output
- Create execution scripts and save all scripts

#### Triggers:

- Create a trigger (INSERT, UPDATE, or DELETE)
- For an “excellent” grade: the trigger should automate business processes
- Create a test script and save all scripts.

#### Backup:

- Backup the database and save a .bak file
- Generate a script from SSMS for the entire database and all database objects:
  - All tables, views, procedures, etc.
  - All logins, users, roles
  - All data *without* DROP statements
  - Save the two database files (.mdf and .ldf, if applicable).
- For an “excellent” grade:
  - Create a CURSOR script if needed by the business logic
  - Alternatively, import data (e.g., from EXCEL)
  - Alternatively, connect Access/Excel/Power BI as a front-end (develop 1 form and 1 report)
  - Alternatively, implement a 1:1 relationship or circular reference + views
  - Alternatively, add additional functions, procedures, and/or triggers

#### Project Documentation:

- Include a brief project description (see example template) as a .pdf
- Add a database diagram

#### General Guidelines:

- Sample scripts from exercises can be used as templates
- Use original naming conventions (D/EN, in camelCase or PascalCase) for all functions, variables, field names, etc.
- All scripts and functions should be well-commented (preferably in German, but English is also acceptable)

If time permits, enhance your project based on your interests and expertise (add more tables, functions, procedures, etc.).

### Format:

Working in Groups of 4 people - so I didn't do this project on my own.

### Repository contents:

- ERM of the database
- SQL-Script with all CREATE Statements
- .db file
