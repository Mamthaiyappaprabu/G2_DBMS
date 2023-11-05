# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE :
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
 create table student(rollno int,name char(40),age int,address varchar(50),phoneno int);
```

### OUTPUT:
![1](https://github.com/Mamthaiyappaprabu/G2_DBMS/assets/119393563/c373d71a-91bc-4ce3-bf76-0dc36f916098)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(50);
```

### OUTPUT:

![2](https://github.com/Mamthaiyappaprabu/G2_DBMS/assets/119393563/4ac9e6fc-b83d-43c1-82ed-b39af13b8274)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```

### OUTPUT:

![drop](https://github.com/Mamthaiyappaprabu/G2_DBMS/assets/119393563/30b61eaa-0282-42b1-82e0-f71d6fc1c681)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:

![3](https://github.com/Mamthaiyappaprabu/G2_DBMS/assets/119393563/b68216b9-00cf-4fa3-b025-788b75f6b698)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```

### OUTPUT:
![4(1)](https://github.com/Mamthaiyappaprabu/G2_DBMS/assets/119393563/4c7bdff5-4934-4667-95ad-9911dd6e4ba2)
![4(2)](https://github.com/Mamthaiyappaprabu/G2_DBMS/assets/119393563/05636ef7-70f7-441d-b804-bd29fb2b40dc)


### RESULT:

To create a student database and execute DDL queries using SQL is executed successfully.
