## Database
- A collection of information that is organized so that it can easily be accessed, managed and updated.
- It is a collection of tables.
  - A table is a collection of related data entries in the form of rows and columns

## SQL 
- Structured query languages used to communicate with the database
- It executes query against a database to retrieve data or insert, update and delete records in the database.
- SQL can create new databases.
- SQL can create new tables in a database.
- SQL can create stored procedures in a database.
- SQL can delete records from a database and create views in a database.

## DBMS
- Database Management System is software through which we execute SQL queries.
  - MySQL, Oracle, SQLite.
- There is only slight difference between all the different databases.
- MYSQL is one of the database management systems
  - It is open source dbms and can be used for free.
  - It runs on almost all the platforms and have good performance results.

### SQL is a query language whereas MySQL is a database to support SQL.

## Download MYSQL complete product form
- A server and editor is required to write sql queries and create database.
- [MySQL Download](https://dev.mysql.com/downloads/windows/installer)
- Download the community version, select platform and OS architecture 32 bit or 64 bit.
- Follow all the steps to install after the download completes.
- Connect to the internet to download all the updates.
- Select developer default to install all the components required and default path for the installation.
- Click execute to proceed and it takes 10-15 minutes for the installation.
- Click on configuration and then enter the default SQL root password and add user.

## Overview of SQL editor
- Open MySQL Workbench from C:Program Files path or desktop icon.
- Connect to the server to access all the databases stored on the server.
- User is root and enter the password which was setup during the installation.
- In the left hand side we can check all the databases and expand it further to see tables and columns
- In the editor, we can write the query and run, save the file

## Creating a database.
```
Create Database Demo_Gamer;
```
- Command to create the database.
- Click on first icon to executed the selected command or all the queries in the editor.
- Once executed, database will be created and will be visible in the left side after refresh.

## Creating a Table 
```
use Demo_Gamer;
```
- Use this database
```
create table employee_info(employee_name varchar(20), id int, location varchar(15), age int);
```
- Created a table name employee_info

## Describe the table
``` describe employee_info;  ```
- Show information about employee table

## Inserting the values into the table
```
insert into employee_info values('Roh', 1, 'Delhi', 25)
```
```
insert into employee_info values('Ram', 2, 'Gurgaon', 24)
```
```
insert into employee_info('Aam', 3, 'Mumbai', 21)
```
```
insert into employee_info values('Shyam', 4, 'Kolkata', 22)
```
```
insert into employee_info values('Shyam', 3, 'Kolkata', 21)
```
- Inserted four values (rows and columns) in the table.

## Retrieving the values from the table
```Select * from employee_info; ```
- All the columns in the table will be retrieved using asterisk 
```Select employee_name,id,location,age from employee_info; ```
- Select keyword is used to retrieve the records from the table.

```Select employee_name,age from employee_info; ```
-Specific data from the table

## Distinct Keyword in queries
```use employee_info;```

``` 
select distinct employee_name from employee_info;
```
- Using distinct keyword we will get only unique name from the employee table column name 

## SQL Where command usage
- Get the employee names of Gurgaon.
``` 
    select employee_name from employee_info 
    where location = 'Gurgaon';
```
- Get the employee names of Kolkata and age is more than 21
``` 
    select employee_name from employee_info 
    where location = 'Kolkata' AND age > 21;
```
- Get the employee names of Mumbai and age should be less than 24 or location could be Delhi
``` 
    select employee_name from employee_info 
    where (location = 'Mumbai' and age < 24) or location = 'Delhi;
```
## Logical Operator And OR
``` 
    select employee_name from employee_info where id = 1 or id =2;
```
- Employee with id 1 or 2 in the table
 ```   
    select employee_name from employee_info where id = 1 and location = 'Delhi'
```
- Employee name with id 1 and from Delhi 
```
    select employee_name from employee_info where age in(23,24,25)
```
- Get the employees whose age are in between 23 and 25
```
select employee_name from employee_info where location in ('Delhi','Gurgaon','Mumbai')
```
-  Get the employees whose location is Delhi, Gurgaon and Mumbai

## Logical Operator 'In' 'Between'
- Get the employees name whose id lies between 1 and 100
```
select employee_name from employee_info where id between 1 and 100;
```
- Get the employees name whose age is less than age 25
```
    select employee_name from employee_info where age < 25;
    select employee_name from employee_ where age in(1,2,3,4,5.....,24,25);
    select employee_name from employee_ where age between 0 and 25;
```
- Get the employees name whose age is not between 25 and 100
```
    select employee_name from employee_ where age not between 25 and 100;
```
- Not between is useful to make the query shorter.
  
## Regular expressions
- % it stands for any characters like abcde, we can put a% to get any letters after a.
  - It prints all the names which starts with a and any any character after that.
- _ underscore stands for one letter (whatever it can be) 
- _b% represents name starts with any letter and then the second letter is b whereas after that it can have any letter
- __c% in this scenario, first two letter could be anything and third letter is c, after that any number of random letters can be there.

- Print the names with 3 letters where 1st letter be d.
  ``` d__ ```
