MySQL Command Line Interface
===============

Related tutorial: http://cd64.de/mysql-cli


Commands
-----------

Access monitor: `mysql -u [username] -p` (will prompt for password)

Show all databases: `show databases;`

Access database: `mysql -u [username] -p [name-of-database]` (will prompt for password)

Create new database: `create database [name-of-database];`

Select database: `use [name-of-database];`

Show all tables: `show tables;`

Show table structure: `describe [name-of-table];`

Create new table with columns: `CREATE TABLE [name-of-table] ([name-of-column] VARCHAR(120), [name-of-another-column] DATETIME);`

Adding a column: `ALTER TABLE [name-of-table] ADD COLUMN [name-of-column] VARCHAR(120);`

Adding a column with an unique, auto-incrementing ID: `ALTER TABLE [name-of-table] ADD COLUMN [name-of-column] int NOT NULL AUTO_INCREMENT PRIMARY KEY;`

Inserting a record: `INSERT INTO [name-of-table] ([name-of-column], [name-of-another-column]) VALUES ('[custom-input]', [custom-input]');`

MySQL function for datetime input: `NOW()`

Selecting records: `SELECT * FROM [name-of-table];`

Selecting parts of records: `SELECT [name-of-column], [name-of-another-column] FROM [name-of-table];`

Logout: `exit`