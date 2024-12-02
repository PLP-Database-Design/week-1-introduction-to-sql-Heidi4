# Database Management System (DBMS) Assignment

## 1. Components of a DBMS

A Database Management System consists of the following major components:

1. **Hardware**: The physical devices that store and process the data (computers, storage devices)
2. **Software**: The actual DBMS software and related applications
3. **Data**: The actual information stored in the database
4. **Procedures**: Rules and instructions for designing and using the database
5. **Query Language**: Languages like SQL that allow users to interact with the database
6. **Users**: Different types of users who interact with the system (administrators, developers, end users)

## 2. Relational Database

A relational database is a type of database that stores and organizes data in tables with rows and columns, where relationships can be established between these tables using keys.

Examples of relational databases:
1. MySQL
2. PostgreSQL
3. Oracle
4. Microsoft SQL Server

## 3. Classifications of SQL

SQL commands are classified into three main categories:

1. **DDL (Data Definition Language)**
   - Used to define and modify database structure
   - Commands include CREATE, ALTER, DROP, TRUNCATE

2. **DML (Data Manipulation Language)**
   - Used to manipulate data within the database
   - Commands include SELECT, INSERT, UPDATE, DELETE

3. **DCL (Data Control Language)**
   - Used to control access to data in the database
   - Commands include GRANT and REVOKE

## 4. Primary Key vs Foreign Key

**Primary Key:**
- Uniquely identifies each record in a table
- Must contain unique values and cannot be null
- Only one primary key per table

**Foreign Key:**
- References a primary key in another table
- Creates relationships between tables
- Can contain duplicate values and can be null
- A table can have multiple foreign keys

## 5. Entity-Relationship Diagram (ERD)

An Entity-Relationship Diagram is a visual representation of the relationships between different entities (tables) in a database. It shows:
- Entities (objects or concepts)
- Attributes (properties of entities)
- Relationships between entities
- Cardinality (one-to-one, one-to-many, many-to-many relationships)

## 6. Advantages of Relational Databases

1. Data Independence
2. Data Integrity and Accuracy
3. Complex Query Capabilities
4. Data Consistency
5. Data Security
6. Reduced Data Redundancy
7. Easy Data Access and Retrieval
8. ACID Properties (Atomicity, Consistency, Isolation, Durability)

## 7. Four Types of Data Types

1. **Numeric Types**
   - INTEGER
   - DECIMAL
   - FLOAT
   - DOUBLE

2. **String Types**
   - VARCHAR
   - CHAR
   - TEXT

3. **Date/Time Types**
   - DATE
   - TIME
   - TIMESTAMP

4. **Boolean Type**
   - BOOLEAN (TRUE/FALSE)

## 8. Purpose of a Database Management System (DBMS)

The main purposes of a DBMS are:

1. **Data Management**: Efficiently organize, store, and retrieve data
2. **Data Security**: Control access to data through authentication and authorization
3. **Data Integrity**: Ensure accuracy and consistency of data
4. **Concurrent Access**: Allow multiple users to access data simultaneously
5. **Data Recovery**: Provide backup and recovery mechanisms
6. **Data Independence**: Separate the physical storage of data from its logical representation
7. **Data Administration**: Centralize the management of data