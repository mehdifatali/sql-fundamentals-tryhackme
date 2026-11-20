# SQL Fundamentals – My Learning Notes

## 1. What is SQL?
SQL (Structured Query Language) is a language used to communicate with relational databases. It allows users to query, retrieve, insert, update, and manage data.

## 2. What is DBMS?
DBMS (Database Management System) is software that acts as an interface between an end user and a database.

**Examples:**
- MySQL
- MariaDB
- Oracle Database
- Microsoft SQL Server

## 3. Relational vs Non-Relational Databases

- **Relational Databases:** Store data in structured tables consisting of rows and columns.
- **Non-Relational Databases:** Store data using flexible models such as documents, key-value pairs, and graphs.

## 4. Database Structure

- **Table:** A structure used to organize data.
- **Row / Record:** A single record in a table.
- **Column / Field:** An attribute that describes the stored data.

## 5. Primary and Foreign Keys

- **Primary Key (PK):** Uniquely identifies each record in a table.
- **Foreign Key (FK):** References a key in another table and establishes a relationship between tables.

## 6. Basic MySQL Commands

### Connect to MySQL
```bash
mysql -u root -p
```

### Show available databases
```sql
SHOW DATABASES;
```

### Select a database
```sql
USE database_name;
```

### List tables
```sql
SHOW TABLES;
```

### Retrieve all records
```sql
SELECT * FROM table_name;
```

## 7. Key Takeaways

- SQL is primarily used to interact with relational databases.
- DBMS provides an interface for managing databases.
- Primary and Foreign Keys establish data identification and relationships.
- MySQL commands allow users to navigate databases and retrieve stored information.

## Learning Source
TryHackMe – SQL Fundamentals
