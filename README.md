College Placement Management System
Overview
The College Placement Management System is a MySQL database project designed to manage college recruitment and placement activities. It stores and organizes information about students, departments, skills, companies, job roles, placement drives, applications, interviews, selections, and job offers.
Objectives
- Maintain structured student and department records.
- Track student skills and placement eligibility.
- Manage company details, job roles, and placement drives.
- Record student applications and interview rounds.
- Track selection results and job offers.
- Generate useful placement reports using SQL queries and views.
Technologies Used
- Database: MySQL 8.0+
- Database client: MySQL Workbench
- Language: SQL
Database Structure
The database is named college_placement_db and includes these 12 tables:
1. departments — department details.
2. students — student academic and placement information.
3. skills — skill catalogue.
4. student_skills — skills and proficiency associated with students.
5. companies — recruiter/company details.
6. job_roles — job openings and eligibility requirements.
7. placement_drives — placement drive schedules and status.
8. company_drives — companies participating in each drive.
9. applications — student applications and eligibility status.
10. interview_rounds — interview schedules, scores, and feedback.
11. selections — final selection outcomes.
12. offers — offer details, CTC, and joining date.
SQL Features
The SQL script includes:
- Database and table creation with primary keys and foreign keys.
- Sample data for demonstration.
- Constraints to validate data such as CGPA, backlogs, scores, and dates.
- Indexes to support commonly used searches.
- Views for combined reporting across related tables.
- Stored procedures for reusable database operations.
- Triggers for validation and automatic handling of selected events.
- Query examples and demo/test queries.
