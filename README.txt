# University Management System - SQL Project

This project is a **University Management System** built using SQL with a focus on handling students, departments, courses, instructors, exams, attendance, and library management. The project is designed to work on a **XAMPP server** and uses MySQL as the database.

## Features

- **Student Management**: Handles student information and their relationship with departments.
- **Course Enrollment**: Manages courses, instructors, and student enrollments.
- **Library System**: Tracks book issues and returns through library transactions.
- **Result Management**: Tracks exam results and student performance.
- **Attendance Tracking**: Monitors student attendance records.

## Database Structure

The database includes the following tables:
- **Student**
- **Department**
- **Course**
- **Instructor**
- **Subject**
- **Batch**
- **Enrollment**
- **Result**
- **Exam**
- **Attendance**
- **Library**
- **Library Transaction**

## Queries
The project includes SQL queries for:
- Aliases, AVG, SUM, MAX, MIN, COUNT
- Inserting and updating data
- Filtering data using WHERE, LIKE, BETWEEN, and more

## Installation

1. Set up **XAMPP** and start Apache and MySQL servers.
2. Import the SQL file provided to create the database schema.
3. Adjust the database configurations as needed.
4. Use the `requirements.txt` to install any required Python libraries if applicable.

```bash
pip install -r requirements.txt
