# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:

### 1) Create a database studentdb

### SQL QUERY:

create database student_db;

### OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/a9370034-b02c-4e63-9398-979e758d1b76)


### 2) Create a table student  and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 

create table student(Regno int,Name varchar(20),Age int,Address varchar(50),Phonenumber varchar(10));

### OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/77c880ff-6d2a-4feb-96a4-1b1e133e2274)


### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 

alter table student
add dept varchar(20);

### OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/0a98430f-8ac7-4e1e-8bdc-e2c995265b88)


### 4) Rename the student table to mystudent

### SQL QUERY: 

drop table student;

### OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/eb421830-1df7-4bb7-8a13-bb7b79351e4c)


### 5) Delete the mystudent rows using truncate keyword

### SQL QUERY:

truncate table student;

### OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/fe22f32f-4ac2-4f1a-998d-aae667faa832)

### 6) Drop the mystudent table
 
### SQL QUERY: 

alter table student
rename to mystudent;

### OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/088c6319-401e-4bde-b073-08478f548ff2)


## Result:
         Thus the basic DDL commands in SQL are executed. 


