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
DEVELOPED BY: SOUNDARIYAN M.N
REG MO: 212222230146
```
### 1) Create a database studentdb

### SQL QUERY:
```
create database student_db;
```

### OUTPUT:
![image](https://github.com/soundariyan18/DBMS/assets/119393307/c8174148-168b-45aa-ba7a-318d8075aaaf)


### 2) Create a table student with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
```
create table student(Regno int,Name varchar(20),Age int,Address varchar(50),Phonenumber varchar(10));
```


### OUTPUT:
![image](https://github.com/soundariyan18/DBMS/assets/119393307/f6887924-8398-4fb6-acee-2565166008a5)


### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student
add dept varchar(20);
```

### OUTPUT:
![image](https://github.com/soundariyan18/DBMS/assets/119393307/cc8d8386-d04c-483d-8207-cf62edd0bdef)



### 4) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```


### OUTPUT:
![image](https://github.com/soundariyan18/DBMS/assets/119393307/3cdf81d9-a5ab-4705-ae02-2cf2ff1c133f)



### 5) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```


### OUTPUT:
![image](https://github.com/soundariyan18/DBMS/assets/119393307/b4f551cd-1f51-40ec-b1fd-9a1de06bf1d2)




### 6) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student
rename to mystudent;
```



### OUTPUT:
![image](https://github.com/soundariyan18/DBMS/assets/119393307/a475705e-596f-40fd-a4b0-c5d4be004c87)



## Result:
Thus the basic DDL commands in SQL are executed. 


