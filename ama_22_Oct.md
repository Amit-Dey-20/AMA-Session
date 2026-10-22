# AMA Questions and Answers

## What are joins in SQL?
### Answer:
Joins in SQL are used to combine data from two or more tables based on a related column between them.


## What are the different types of joins?
### Answer:
- INNER JOIN: Returns only matching rows from both tables.

- LEFT JOIN: Returns all rows from the left table and matching rows from the right table.

- RIGHT JOIN: Returns all rows from the right table and matching rows from the left table.

- FULL OUTER JOIN: Returns all rows from both tables, whether they match or not.

- CROSS JOIN: Returns the Cartesian product of both tables.

- SELF JOIN: Joins a table with itself.


## What are LIMIT and OFFSET in SQL?
### Answer:
- LIMIT specifies the maximum number of rows to return.

- OFFSET specifies the number of rows to skip before returning results.

## What is the GROUP BY clause?
### Answer:
The GROUP BY clause is used to group rows that have the same values in specified columns. It is often used with aggregate functions like COUNT(), SUM(), AVG(), MAX(), and MIN().


## What is atomicity in DBMS?
### Answer:
Atomicity in DBMS is a property of a transaction that ensures all operations are completed successfully, or none of them are applied.

## What is the HAVING clause in SQL?
### Answer:
The HAVING clause is used to filter grouped results, usually after applying the GROUP BY clause. It is commonly used with aggregate functions such as COUNT(), SUM(), and AVG().


## What is the difference between JOIN and UNION?
### Answer:
- JOIN combines columns from two or more tables based on a related column.

- UNION combines rows from two or more SELECT queries. The queries must return the same number of columns with compatible data types.

## What is the difference between UNION and UNION ALL?
### Answer:
- UNION combines the results of two or more SELECT queries and removes duplicate rows.

- UNION ALL combines the results and keeps all duplicate rows.


## What is a transaction in DBMS?
### Answer:
A transaction in DBMS is a group of database operations performed as a single logical unit of work. It either completes successfully or is rolled back if an error occurs.


## What is normalization in DBMS?
### Answer:
Normalization is the process of organizing data in database tables to reduce data redundancy (duplication) and improve data integrity.