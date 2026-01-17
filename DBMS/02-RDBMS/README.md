# RDBMS (Relational Database Management System)

Notes based on takeUforward (Striver DBMS sheet) – RDBMS section.

---

## 1. What is RDBMS

- RDBMS stands for **Relational Database Management System**.
- Data is stored in the form of **tables (relations)**.
- Tables consist of **rows (tuples)** and **columns (attributes)**.
- Relationships between tables are defined using **keys**.
- Data is accessed and manipulated using **SQL (Structured Query Language)**.

### Examples
- MySQL
- PostgreSQL
- Oracle
- Microsoft SQL Server

---

## 2. Table in RDBMS

- A **table** is a structured collection of related data.
- Data is stored in **rows and columns**.
- Each table represents a real-world entity.

---

## 3. Row (Tuple)

- A row represents a **single record** in a table.
- Each row contains values for all attributes of the table.
- **Cardinality** refers to the **number of rows** in a table.

---

## 4. Column (Attribute)

- A column represents a **field or property** of an entity.
- All values in a column belong to the **same domain**.
- **Degree** refers to the **number of columns** in a table.

---

## 5. Keys in RDBMS

### Primary Key
- A primary key uniquely identifies each record in a table.
- It cannot contain NULL values.
- Each table can have **only one primary key**.

### Foreign Key
- A foreign key refers to the primary key of another table.
- It establishes a **relationship between two tables**.
- Helps maintain **referential integrity**.

---

## 6. Constraints in RDBMS

Constraints are **rules applied on table data** to ensure data accuracy and integrity.

### NOT NULL
- Ensures a column cannot have NULL values.

### UNIQUE
- Ensures all values in a column are unique.

### CHECK
- Ensures values satisfy a specific condition.

### DEFAULT
- Assigns a default value to a column if no value is provided.

---
