
## 1. Components of a DBMS
A DBMS consists of the following core components:

1. Hardware
Hardware refers to the physical, electronic devices such as computers and hard disks that offer the interface between computers and real-world systems.

3. Software
Software is a set of programs used to manage and control the database and includes the database software, operating system, network software used to share the data with other users, and the applications used to access the data.

3. Data
Data are raw facts and information that need to be organized and processed to make it more meaningful. Database dictionaries are used to centralize, document, control, and coordinate the use of data within an organization. A database is a repository of information about a database (also called metadata).

4. Procedures
Procedures refer to the instructions used in a database management system and encompass everything from instructions to setup and install, login and logout, manage the day-to-day operations, take backups of data, and generate reports.

5. Database Access Language
Database Access Language is a language used to write commands to access, update, and delete data stored in a database. Users can write commands using Database Access Language before submitting them to the database for execution. Through utilizing the language, users can create new databases, tables, insert data, and delete data.


## 2. What is a Relational Database? 
A relational database organizes data into tables (relations) with rows (tuples) and columns (attributes). Relationships between tables are defined using keys.

### Examples:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

## 3. Classifications of SQL
1. **Data Definition Language (DDL)**:
   - Commands used to define the database structure.
   - Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.

2. **Data Manipulation Language (DML)**:
   - Commands used to retrieve and manipulate data.
   - Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

3. **Data Control Language (DCL)**:
   - Commands used to control access to data.
   - Examples: `GRANT`, `REVOKE`.

## 4. Difference Between Primary Key and Foreign Key
Primary key is a unique identifier for each record in a table whereas a foreign key is a reference to a primary key in another table

## 5. What is an Entity-Relationship Diagram (ERD)?
An **Entity-Relationship Diagram (ERD)** is a graphical representation of entities, their attributes, and the relationships between them in a database. It helps in designing and understanding the database structure.



## 6. Advantages of Relational Databases
1. **Data Integrity**: Enforces data consistency using constraints like primary and foreign keys.
2. **Flexibility**: Allows complex queries and relationships between tables.
3. **Scalability**: Handles large volumes of data and concurrent users efficiently.
4. **Security**: Provides robust authentication and access control mechanisms.


## 7. Types of Data Types in Tables
1. **Integer Types**: Used for whole numbers (e.g., `INT`, `SMALLINT`).
2. **Character Types**: Used for strings (e.g., `CHAR`, `VARCHAR`).
3. **Date/Time Types**: Used for date and time values (e.g., `DATE`, `TIMESTAMP`).
4. **Floating-Point Types**: Used for decimal numbers (e.g., `FLOAT`, `DOUBLE`).

## 8. Purpose of a Database Management System (DBMS)
The primary purpose of a DBMS is to provide an interface for users to efficiently store, retrieve, and manage data while ensuring:
1. **Data Integrity**: Enforces constraints and relationships.
2. **Data Security**: Restricts unauthorized access.
3. **Data Consistency**: Ensures reliable and accurate data storage.
4. **Multi-User Support**: Facilitates simultaneous data access by multiple users.
5. **Backup and Recovery**: Protects data from loss due to failures.