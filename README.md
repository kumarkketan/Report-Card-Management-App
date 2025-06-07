# **Student Report Card Management System (MySQL + Python)**

Welcome to my Student Report Card Management System — a command-line Python project that integrates MySQL for backend operations and focuses on data validation, storage, manipulation, and analysis of student records. This project was developed to simulate real-world data handling, from entry to dynamic reporting, making it a solid addition to my data analyst portfolio.

## About the Project

This project allows users (like admins or school staff) to manage student records via a user-friendly command-line interface. It supports the following operations:

-  Add new student records

-  View student details by ID

-  Update student personal details or subject marks

-  Delete a student’s record

-  Auto-generate a detailed report card with percentage, grade, and result status (Pass/Fail)

I built this project as part of my journey into data analysis, and it reflects key concepts like:

- Structured data storage using SQL

- Data validation and sanitization

- Conditional logic for decision making

- Automated reporting output with clean formatting

- Error handling for robustness

## Tech Stack Used

-   Python - Core programming language for logic and flow

-  MySQL -	Database used for storing student data

- MySQL Connector	- Python-MySQL bridge for executing SQL queries

-  ANSI Color Codes	- For enhanced user experience in terminal output

## 📊 Data Analysis Concepts Used

This project simulates foundational data analysis operations:

- Data collection (via user input)

- Data validation (checking types, ranges, and constraints)

- Data cleaning (ensuring only valid records are inserted)

- Data transformation (converting marks into percentages, grades)

- Data presentation (well-formatted report card as an output)

## 📁 Features Overview

✅ Add Student

→ Enter student name, age, selected course, and marks in five subjects (Python, NumPy, Pandas, SQL, Power BI).

→ Validation is applied to ensure data correctness.

✅ View Student

→ Retrieve student ID, name, age, and course with one input.

✅ Update Student

→ Update either personal details, marks, or both.

✅ Delete Student

→ Remove a student record with confirmation to prevent accidental deletions.

✅ Generate Report Card

→ Calculates total marks, percentage, grade, and pass/fail status.

→ Well-formatted visual output generated dynamically using string formatting and borders.

