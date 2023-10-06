# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBM

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
#### SQL QUERY: 
```sql
SQL> CREATE TABLE student(roll_no int, name varchar(20), age number,
address varchar(100), phoneno number(10));
```
#### OUTPUT:
![dbms_1 1](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/c674d16c-f536-4648-8522-dff3fd1deebd)


### 2) Change the above student table by adding another attribute department
#### SQL QUERY: 
```mysql
SQL> ALTER TABLE student ADD dept varchar(10);
```
#### OUTPUT:
![dbms_1 2](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/75ddcbb9-b773-4602-9993-fb4ea6510504)


### 3) Drop the student table
#### SQL QUERY: 
```sql
SQL> DROP TABLE student;
```
#### OUTPUT:
![dbms_1 3](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/be3a2fca-1dfd-4af8-853e-39daac9d169d)


### 4) Delete the student table using truncate keyword
#### SQL QUERY: 
```sql
SQL> TRUNCATE TABLE student;
```
#### OUTPUT:
![dbms_1 4](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/d2a70db5-1575-4235-b875-3fea0f4194d7)


### 5) Rename the student table to mystudent
#### SQL QUERY: 
```sql
SQL> ALTER TABLE student RENAME TO mystudent;
```
#### OUTPUT:
![dbms_1 5](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/87958e70-c3da-4a78-aded-58116b6a03d4)


## RESULT:
Thus the table student database is created and DDL queries are executed successfully.
