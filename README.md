# Working-with-RDMBS-via-Python-env.
Basic knowledge upon databases, SQL, SQL API and SQL Magic commands in Jupyter% environment
----
### I, Databases:
1. What is a database?
2. Relational databases model vs Entity-relationship model
3. SQL
4. SQLite vs MySQL
-----   
### II, SQL: Create a table_Working with RDMBS using Magic commands and API
1. What is SQL:
    - Intro
    - Types of SQL statments
    - Interacting with RDBMS from a Python environment
2. SQL magic commands to work with RDBMS via a Python environment:
    - create and connect to a database 
    - CREATE statement
    - Primary key
    - SQL data types
    - SQL column constraints
3. sqlite3 API to interact with SQLite RDBMS via a Python environment:
    - load data from a csv file into a sql-database
    - .execute() vs .executemany()
---- 
### III, SQL: Query data based on criteria _ Deal with null values _ Create a table from others
1. SELECT statement:
- Query all the data from the table
- Query specified columns
- Show the number of rows within the table: COUNT()
- Show unique values: DISTINCT 
- Show the number of unique values: COUNT(DISTINCT )
- NESTED STATEMENTS
2. WHERE statement:
- pass the condition into the query
- Logical operators
- Deal with missing values: null or empty strings?
3. Wildcards and LIKE operator:
- Query rows associated with values that are partly remembered
4. Create a table from other tables: CREATE TABLE tab_name AS
----  
### IV, SQL _ Mathematical functions _ Delete, Sort rows
- Sum of rows: SUM()
- Delete specified rows: DELETE FROM
- Sort rows: ORDER BY
- Average of rows: AVG()
- Filter out: WHERE + Nested statements
- Min and max values: MIN() MAX()
----
### V, SQL _ meta data of the database _ interact with the data and the table structure
1. sqlite_master:
- Check the name of all tables
- Check the properties of a table
2. Interact with tables within the database: 
- Create a copy of a table: 
- Add new columns to a table: ALTER TABLE tab_name ADD 
- Update the values of a row: UPDATE tab_name Set col = val WHERE 
- Rename a table
- Find the average number associated with each value within a category: GROUP BY
- Filter output: HAVING vs WHERE
- Logical operators: BETWEEN AND
- Truncate a table: TRUNCATE TABLE
- Drop a table: DROP TABLE
----
### VI, SQL: .execute() vs .executemany() _ LIMIT num _ JOIN _ Call out columns from tables
- Load the data sql
- Create sql tables within the database, DROP TABLES IF EXISTS to enhance the smooth flow of our code execution
- Load data from a csv file into a RDBMS using sqlite3: .execute() vs .executemany(string, list_of_rows)
- Save the tables
- Show specific number of rows: LIMIT num
- Create a new table from two different tables: types of JOIN and Call out columns from a table
----
### VII, qlite3 to work with RDBMS via a Python environment
- cursor.fetchall() vs cursor.fetch()

  
