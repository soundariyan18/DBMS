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
```
DEVELOPED BY: Barath S
REG MO: 212222230018
```
### 1) Create a database studentdb

### SQL QUERY:
```
create database student_db;
```

### OUTPUT:
![model](o1.png)

### 2) Create a table student with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
```
create table student(Regno int,Name varchar(20),Age int,Address varchar(50),Phonenumber varchar(10));
```


### OUTPUT:
![model](o2.png)

### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student
add dept varchar(20);
```

### OUTPUT:
![model](o3.png)


### 4) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```


### OUTPUT:
![model](o4.png)


### 5) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```


### OUTPUT:
![model](o5.png)



### 6) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student
rename to mystudent;
```



### OUTPUT:
![model](o6.png)


## Result:
Thus the basic DDL commands in SQL are executed. 


