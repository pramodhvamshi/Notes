# Introduction to DBMS

Notes prepared from handwritten study based on Striver / takeUforward DBMS sheet.

---

## 1. Data, Database and File System

### Data
- Data refers to a collection of raw facts or figures.
- Any fact that can be stored is considered data.
- Example: numbers, characters, symbols.
- **Processed data becomes information**.

### Database
- A database is a **collection of interrelated data**.
- Data is generally stored in the form of **tables**.
- A database can be of **any size**.
- Examples:
  - College database
  - Student placement database
  - Multimedia database (images, videos)

### File System
- A file system is an **OS approach** to organizing and storing data on storage devices like hard disks.
- In a file system, data is organized into **files**.

### Disadvantages of File System
- Data redundancy
- Poor memory utilization
- Data inconsistency
- Weak data security

---

## 2. What is DBMS

- DBMS stands for **Database Management System**.
- It is a software system that allows users to:
  - Store data
  - Retrieve data
  - Update data
  - Manage data safely and efficiently
- DBMS works using a **program or a set of programs**.
- Rules and regulations in DBMS are essential to maintain and manage databases effectively.

---

## 3. Applications of DBMS

### Schools & Colleges
- DBMS is used to create and maintain student information systems.
- It stores and manages student-related data efficiently.

### Banks
- DBMS is used to maintain a **centralized and secure database**.
- Customer information is stored safely and accessed efficiently.

---

## 4. Need of DBMS

- DBMS plays a **vital role for businesses, institutions, and organizations** of all sizes.
- It helps in:
  - Effective data management
  - Ensuring data accuracy
  - Maintaining data security
  - Supporting decision-making processes
- DBMS acts as the **core of modern information systems**.
- It provides the foundation for a wide range of applications and services.

---

## 5. Advantages of DBMS

### Data Security
- DBMS enforces security mechanisms.
- It regulates access to sensitive information.
- Protects data from unauthorized access and data breaches.

### Reduced Data Redundancy and Inconsistency
- DBMS minimizes data redundancy.
- Ensures consistency by maintaining a unified version of data.

### Data Integrity
- DBMS enforces integrity rules and constraints.
- Prevents incorrect or inconsistent data entry.

### Data Scalability
- DBMS can handle large databases.
- It scales efficiently as the organization grows.

---

## 6. Disadvantages of DBMS

### High Cost
- Cost of acquiring, deploying, and maintaining DBMS software is high.
- Requires powerful hardware for efficient operation.

### Complexity for Small Applications
- For small-scale applications with minimal data, DBMS may introduce unnecessary complexity.
- Simpler storage alternatives may be more suitable.

### Vendor Lock-in
- Switching DBMS vendors is difficult.
- Differences in data formats and query languages may cause dependency on a specific vendor.

---

## 7. Types of Databases

- RDBMS
- NoSQL Databases
- Object-Oriented Databases
- In-Memory Databases
- Time-Series Databases
- Spatial Databases
- Multimedia Databases
- Columnar Databases
- XML Databases
- NewSQL Databases
- Blockchain Databases

### RDBMS
- Structures data into organized tables.
- Relationships between tables are predefined.
- Data manipulation and querying are done using **SQL**.
- Examples: MySQL, PostgreSQL, Oracle, Microsoft SQL Server.

### NoSQL Databases
- Designed to handle data that does not fit into rigid relational schemas.
- Suitable for large-scale and unstructured data.
- Example: MongoDB.

### Object-Oriented Databases
- Store data as objects (data + actions).
- Used in object-oriented programming environments.
- Suitable for complex data like simulations and multimedia applications.

---

## 8. Data Abstraction

- DBMS provides data abstraction.
- It allows users and applications to interact with the database **without understanding internal complexities**.
- Improves usability and simplifies database interaction.
