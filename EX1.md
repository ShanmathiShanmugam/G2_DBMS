# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: CREATE TABLE student_1 (rollno numeric,name varchar(20),age numeric,address varchar(40),phno numeric);

### OUTPUT:
![Screenshot 2023-10-01 180158](https://github.com/ShanmathiShanmugam/G2_DBMS/assets/121243595/bd18c6d0-edc5-4846-833d-2749744ccddf)

### 2) Change the above student table by adding another attribute department

### SQL QUERY:  ALTER TABLE student_1 ADD dept varchar(15);

### OUTPUT:
![image](https://github.com/ShanmathiShanmugam/G2_DBMS/assets/121243595/b7c4f5cd-3aff-4398-b3e8-0cd442c5695f)

### 3) Drop the student table
 
### SQL QUERY: DROP TABLE mystudent;

### OUTPUT:
![Screenshot 2023-10-01 181018](https://github.com/ShanmathiShanmugam/G2_DBMS/assets/121243595/a9313b70-2d78-485a-8898-77055122c6f5)

### 4) Delete the student table using truncate keyword

### SQL QUERY:  TRUNCATE TABLE student_1;

### OUTPUT:
![Screenshot 2023-10-01 180658](https://github.com/ShanmathiShanmugam/G2_DBMS/assets/121243595/88328a9c-3203-4c4b-9192-4d639323ca3f)

### 5) Rename the student table to mystudent

### SQL QUERY: ALTER TABLE student RENAME TO mystudent;

### OUTPUT:
![Screenshot 2023-10-01 180950](https://github.com/ShanmathiShanmugam/G2_DBMS/assets/121243595/d675bcf9-5560-4253-9d91-5b2ce129298c)
