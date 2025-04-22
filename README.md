# DBMS Lab Experiments

This repository contains MySQL-based implementations for common database operations taught in a **Database Management Systems (DBMS)** lab. Each experiment includes aim, theory, syntax, SQL code, and results where applicable.

> ✅ Designed for students and educators to practice SQL operations and understand database concepts effectively.

---

## 📌 List of Experiments

### 1. Study of ER Diagram
- **Aim:** To understand and draw an Entity-Relationship (ER) diagram based on a university database.
- **Topics Covered:** Entities, Attributes, Primary Key, Relationships, Cardinality.
- **Use Case:** University database involving Students, Courses, Programs.

### 2. Study of DDL Commands in SQL
- **Aim:** To explore and execute SQL DDL commands.
- **Commands Used:**
  - `CREATE TABLE`
  - `ALTER TABLE`
  - `DROP TABLE`
  - `TRUNCATE TABLE`
- **Output:** Table structure modifications.

### 3. Implementation of DML Commands in SQL
- **Aim:** To use DML statements in SQL.
- **Commands Used:**
  - `INSERT`
  - `UPDATE`
  - `DELETE`
- **Output:** Manipulation of records in database tables.

### 4. Set Operations and Clauses
- **Aim:** To perform set operations and apply SQL clauses.
- **Topics Covered:**
  - Set Operations: `UNION`, `INTERSECT`, `MINUS` (if supported)
  - Clauses: `WHERE`, `GROUP BY`, `ORDER BY`, `HAVING`
- **Use Case:** Filtering and grouping employee and department data.

### 5. Single Row and Multi-Row Functions
- **Aim:** To demonstrate SQL functions on records.
- **Functions Used:**
  - Single Row: `UPPER()`, `LOWER()`, `ROUND()`, `NOW()`
  - Multi Row: `SUM()`, `AVG()`, `COUNT()`, `MAX()`, `MIN()`

### 6. Operations on Joins
- **Aim:** To demonstrate different types of joins in SQL.
- **Joins Covered:**
  - `INNER JOIN`
  - `LEFT JOIN`
  - `RIGHT JOIN`
  - `FULL OUTER JOIN` (if supported)
- **Use Case:** Joining `Employees` and `Departments`.

### 7. Subqueries in SQL
- **Aim:** To perform nested queries (subqueries).
- **Subquery Types:**
  - In `WHERE`, `FROM`, `SELECT` clause
  - Single-row & Multi-row subqueries

### 8. Views in MySQL
- **Aim:** To create and manage SQL views.
- **Operations:**
  - `CREATE VIEW`
  - `UPDATE VIEW`
  - `DROP VIEW`
  - Querying views
- **Use Case:** Virtual table for high salary employees and departmental views.

---

## 🧰 Technologies Used
- MySQL (v5.7+ recommended)
- SQL Standard Syntax
- Compatible with MySQL Workbench, phpMyAdmin, or any SQL GUI/CLI tool.

---

## 📁 Folder Structure (Suggested)
```
DBMS-Lab/
├── README.md
├── ER-Diagram/
│   └── university-er.pdf/png
├── Experiment-02-DDL-Commands.sql
├── Experiment-03-DML-Commands.sql
├── Experiment-04-Set-Clauses.sql
├── Experiment-05-Functions.sql
├── Experiment-06-Joins.sql
├── Experiment-07-Subqueries.sql
├── Experiment-08-Views.sql
```

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 🧠 Author
**Your Name**  
B.Tech Student | DBMS Enthusiast

---

## 📜 License
This project is licensed under the MIT License.

---

Feel free to ⭐ star this repo if it helped you in your DBMS lab preparation!
