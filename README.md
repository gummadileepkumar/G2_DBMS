
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
```sql
create table STUDENT(S_Roll_no int,S_Name char(20),S_Age int,S_Address char(30),S_Phone_no int);
```
### OUTPUT:
![dbms_1 1](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/e3041b75-d302-4659-af6e-5dfa3c0669d8)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table STUDENT add S_Dept char(10);
```
### OUTPUT:

![dbms_1 2](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/d8760374-0775-43b7-880b-af2fad95cb3e)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
 drop table STUDENT;
```
### OUTPUT:

![dbms_1 3](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/831026d4-4ef0-4bfd-a9be-89fafd0eb67d)


### 4) Delete the student table using truncate keyword

### SQL QUERY:
```sql
 truncate table STUDENT;
```
### OUTPUT:

![dbms_1 4](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/0836d18c-7113-4f87-89fb-1215c9d61e8c)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
rename table STUDENT to MYSTUDENT;
```
### OUTPUT:
![dbms_1 5](https://github.com/gummadileepkumar/G2_DBMS/assets/118707761/0f0424b6-b54d-4743-8c05-74c3835be352)


### RESULT:
Thus, a student database and execute DDL queries is successfully created using SQL;
