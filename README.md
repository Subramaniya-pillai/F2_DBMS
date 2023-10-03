# EX-01: DATA DEFINITION LANGUAGE COMMANDS IN RDBMS
### AIM:
To create a student database and execute DDL queries using SQL.
### DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>  

### List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

```
Developed By: Subramaniya Pillai B
Register No: 212221230109
```
### Query:
#### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
##### SQL QUERY: 
```sql
create table student(rollno numeric(4), name varchar(50), age numeric(2),
                      address varchar(10), phoneno numeric(10));
```
##### OUTPUT:
![git](./02.png)
#### 2) Change the above student table by adding another attribute department.
##### SQL QUERY: 
```SQL
alter table student add department varchar(4);
```
##### OUTPUT:
![git](./01.png)

#### 3) Drop the student table
##### SQL QUERY: 
```SQL
drop table student;
```
##### OUTPUT:
![git](./03.png)

#### 4) Delete the student table using truncate keyword
##### SQL QUERY: 
```SQL
truncate table student;
```
##### OUTPUT:
![git](./04.png)
#### 5) Rename the student table to mystudent
##### SQL QUERY: 
```SQL
alter table student rename to my_student;
```
##### OUTPUT:
![git](./05.png)
### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
