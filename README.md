# G2_DBMS
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
![Screenshot (136)](https://github.com/Gchethankumar/G2_DBMS/assets/118348224/3622d88a-2221-403f-b1df-a4e33a8ce8bb)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table STUDENT add S_Dept char(10);
```
### OUTPUT:
![Screenshot (137)](https://github.com/Gchethankumar/G2_DBMS/assets/118348224/4696ef1e-8c54-4929-99bc-c2e553e8a241)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
 drop table STUDENT;
```
### OUTPUT:
![Screenshot (138)](https://github.com/Gchethankumar/G2_DBMS/assets/118348224/7d1c8734-8fc1-4400-9fad-dbeadaec0bed)


### 4) Delete the student table using truncate keyword

### SQL QUERY:
```sql
 truncate table STUDENT;
```
### OUTPUT:
![Screenshot (139)](https://github.com/Gchethankumar/G2_DBMS/assets/118348224/3584996e-1358-45fa-883a-fefac09e559e)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
rename table STUDENT to MYSTUDENT;
```
### OUTPUT:
![Screenshot (140)](https://github.com/Gchethankumar/G2_DBMS/assets/118348224/cc72bfa1-c9e7-4200-ade9-b7a72f95a035)

### RESULT:
Thus, a student database and execute DDL queries is successfully created using SQL;
