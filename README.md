# sql-task-library
#Library Management System - SQL Schema

This repository contains the SQL schema and ER diagram for a **Library Management System**, created as part of Task 1 of the SQL Developer Internship.

---

##Tools Used
- **MySQL Workbench**: For writing and running SQL queries
- **dbdiagram.io**: For creating the ER diagram

---

## Files Included
- `library_schema.sql`: Contains SQL code to create database and tables
- `ER-diagram.png`: Diagram showing table relationships
- `README.md`: Explains the schema structure

---

##Tables & Relationships

### Tables Created:
- **Members**
- **Books**
- **Loans**

### Relationships:
- `Loans.member_id → Members.member_id` (Foreign Key)
- `Loans.book_id → Books.book_id` (Foreign Key)

---

##Description

This schema allows:
- Tracking of library members
- Managing books inventory
- Recording borrowing and returning of books via loans

--

