# Summary of SQL Commands: DDL, DML, and TCL
<img src="https://github.com/user-attachments/assets/ab368269-c3f0-42dd-9ffb-c7b5014365c1" width="200" height="200">

## 1. Data Definition Language (DDL):
DDL consists of SQL commands used to define and modify the structure of database objects such as tables, views, and schemas. These commands manage the database schema and automatically commit changes, meaning that they cannot be rolled back once executed.

#### Key DDL commands:
1. CREATE: Used to create new database objects.
2. ALTER: Modifies existing database objects.
3. DROP: Deletes existing database objects.
4. TRUNCATE: Removes all rows from a table.

## 2. Data Manipulation Language (DML):
DML commands are used to interact with and manipulate the data stored in a database. These commands allow users to perform operations such as retrieving, inserting, updating, and deleting data within tables. Unlike DDL, DML operations do not automatically commit; they can be either committed or rolled back, which ensures transactional control over changes.

#### Key DML commands:
1. SELECT: Retrieves data from the database.
2. INSERT: Adds new records to a table.
3. UPDATE: Modifies existing records in a table.
4. DELETE: Removes records from a table.

## 3. Transaction Control Language (TCL):
TCL commands are used to manage transactions within a database. A transaction is a sequence of operations performed as a single logical unit of work. TCL ensures the integrity of the database by controlling whether changes made by DML commands are permanently saved or undone. TCL provides mechanisms to commit, roll back, and manage specific points within a transaction.

#### Key TCL commands:
1. COMMIT: Permanently saves all changes made in the current transaction.
2. ROLLBACK: Reverts the database to the last committed state, undoing any changes made since the last COMMIT.
3. SAVEPOINT: Creates a marker within a transaction to which you can later roll back without affecting the entire transaction.
4. SET TRANSACTION: Defines transaction properties, such as setting the isolation level.

<img src="https://github.com/user-attachments/assets/ac1b2081-157d-4b81-abdb-80cbade637a6" width="1000" height="1000">
