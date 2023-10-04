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

### SQL QUERY: 
```
create table student (rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));
```
### OUTPUT:
![1](https://github.com/Divya110205/G2_DBMS/assets/119404855/191b59d6-f02a-4bd5-8265-ffedd74c6bac)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department varchar(15);
```
### OUTPUT:
![2](https://github.com/Divya110205/G2_DBMS/assets/119404855/6489175b-8d57-47b1-9cda-b30ea6707958)

### 3) Drop the student table
 
### SQL QUERY:
```
drop table student;
```
### OUTPUT:
![3](https://github.com/Divya110205/G2_DBMS/assets/119404855/811cefb1-61b4-4686-98c2-a769575fc617)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![4](https://github.com/Divya110205/G2_DBMS/assets/119404855/d531b49c-230d-4233-804d-7022316880e3)

### 5) Rename the student table to mystudent

### SQL QUERY:
```
rename table student to mysudent;
```
### OUTPUT:
![5](https://github.com/Divya110205/G2_DBMS/assets/119404855/e1dd2d71-fa17-47d8-a546-e85999b1a75d)
