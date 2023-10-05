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
```
DEVELOPED BY : GURUMOORTHI R
REG NO : 212222230042
```
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 

create table stud_table(Roll_no numeric(10) , Name varchar(20) , Age numeric(3), Address varchar(20) , Phone_no numeric(10));


### OUTPUT:

![1](https://github.com/gururamu08/G2_DBMS/assets/118707009/b5226a57-eedd-426a-8f91-6bfbd6c655fe)

![2](https://github.com/gururamu08/G2_DBMS/assets/118707009/6acb43cd-78d7-48dc-8ded-11907e2e2cb7)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
 alter table stud_table add Department varchar(20);

### OUTPUT:

![3](https://github.com/gururamu08/G2_DBMS/assets/118707009/ed68bdbc-0cb7-4bec-833b-c78c092a1804)




### 3) Drop the student table
 
### SQL QUERY: 
drop table stud_table;

### OUTPUT:

![4](https://github.com/gururamu08/G2_DBMS/assets/118707009/13e8cabe-30bf-4284-a693-e3ee212d764f)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table stud_table;

### OUTPUT:

![5](https://github.com/gururamu08/G2_DBMS/assets/118707009/3d943227-a1c9-4653-a7fd-85a21e2419e1)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table stud_table rename to stude;

### OUTPUT:

![6](https://github.com/gururamu08/G2_DBMS/assets/118707009/b5267a2e-ba0b-4cdf-adf4-eea828317a06)

### RESULT:
Thus , a student database is created and DDL queries are executed in SQL.

