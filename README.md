** Employee Attendance & Productivity Analysis (SQL)**
📌 Project Overview

This project focuses on analyzing employee attendance and productivity patterns using SQL.
The objective is to derive actionable business insights from attendance and working-hours data to support workforce planning and productivity improvement.

Unlike common sales or e-commerce projects, this project applies SQL to an HR analytics use case, making it more unique and business-relevant.

🎯 Business Objectives
1. Monitor employee attendance trends over time
2. Identify absenteeism patterns
3. Analyze average working hours by employee and department 
4. Support data-driven workforce and productivity decisions

🗂️ Database Schema (RDBMS)
1️⃣ Employees Table
employees
---------
employee_id (PK)
employee_name
department
joining_date


2️⃣ Attendance Table
attendance
----------
attendance_id (PK)
employee_id (FK)
attendance_date
status (Present / Absent)


3️⃣ Work Hours Table
work_hours
----------
record_id (PK)
employee_id (FK)
work_date
hours_worked


🔹 Relational Design:
1. employee_id acts as a foreign key
2. Tables are linked using JOINs
3. Follows RDBMS normalization principles


🛠️ Tools & Technologies

-SQL (MySQL / PostgreSQL compatible)
-RDBMS Concepts
-Joins, Aggregations, CASE Statements
-Time-based Analysis

📊 Key Analyses Performed
🔹 Employee Attendance Summary
      Total working days
      Present vs absent days per employee

🔹 Department-Wise Attendance
      Absenteeism trends by department

🔹 Productivity Analysis
      Average working hours per employee
      Identification of low-productivity patterns

🔹 Time-Based Analysis
      Monthly attendance and absenteeism trends

📈 Sample Business Questions Answered
  1. Which employees have the highest absenteeism?
  2. Which departments show frequent absences?
  3. Are there monthly or seasonal attendance trends?
  4. Which employees work fewer than average hours?

🧠 Business Insights
*Identified employees with low average working hours
*Detected attendance trends over time
*Highlighted departments with higher absentee rates
*Provided insights useful for HR decision-making and workforce planning

🧾 Project Files

📁 Employee-Attendance-Productivity-SQL
│
├── employee_attendance_analysis.sql
├── README.md
