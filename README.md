# 🗄️ Student Database Management System (MySQL)

## 🚀 Project Overview
This project demonstrates the design and implementation of a relational database system using MySQL to manage student records efficiently.

---

## 🛠️ Tools & Technologies
- MySQL
- SQL Queries

---

## 📁 Database Features
- Student Information Management
- Course Data Handling
- Query-based Data Retrieval

---

## 🧩 SQL Concepts Used
- SELECT, WHERE, ORDER BY
- JOIN (INNER JOIN)
- GROUP BY & Aggregate Functions
- Data Filtering

---

## 📊 Sample Queries

```sql
-- Fetch all students
SELECT * FROM students;

-- Get students with marks above 80
SELECT * FROM students WHERE marks > 80;

-- Join student and course tables
SELECT s.name, c.course_name
FROM students s
INNER JOIN courses c
ON s.course_id = c.course_id;
