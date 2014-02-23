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

Create tables and columns: `CREATE TABLE [name-of-table] ([name-of-column] VARCHAR(120), [name-of-another-column] DATETIME);`

Logout: `exit`