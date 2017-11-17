 # MYSQL
## To start mysql
 `mysql -u root -p then put in password`  

## To show what databases you have
 `show databases;` 
## To create a database
`create Database <database name>;` 
## To use the database
`use <database name>;` 
## To show what tables you have
`show tables;`  
## To create a table
 ```create table <table name> (
 <column name> <column type> <optional specification>,
 <column name> <column type> <optional specification>,
 <column name> <column type> <optional specification>,
 <column name> <column type> <optional specification>,
 <column name> <column type> <optional specification>
 );
 ```

## Options for column type
 
 `int = numbers
 VARCHAR(<length>)
 DATE format yyyy-mm-dd
 options for optional specification:
 NOT NULL
 PRIMARY KEY
 AUTO_INCREMENT
 foriegn key`

## Shows contents of table
 `describe <table name>;` 

## To insert info into the table
 `insert into  <table name> (
 <column name>,<column name>,<column name>,<column name>,<column name>)
 Values
 (
 <value>,<value>,<value>,<value>, <value>
 );` 

## To change the type or  optoinal specifications
 `ALTER TABLE <tablename> MODIFY <columnname> <column type> <optoinal specifications>;` 
## To make changes to the table
 `ALTER TABLE <table name> ADD<column name> <column type> <optional specification>;` 
## To drop a column from a database
`ALTER TABLE <table name> DROP COLUMN <column name>;` 
## To select a column in the table
`select <column name> from <table name>;` 
 
## To see all the column in the table
 `select * from <table name>;` (* = everything)  

## Examples

 `select * from membership where name like "b%"`
  
 `select *  from membership where paid = "no"`
## To delet a value from the table
DELETE FROM table_name WHERE condition;
## To update a table 
UPDATE <table name>  set <column name> WHERE <conditoin>

## Example
`UPDATE students SET seat_location="b-4" WHERE name= ephraim`;
## To do 2  things at once
select * from students where seat_location  like 'a%' and teacher_id=3;
