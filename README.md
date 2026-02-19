DASHBOARD LINK -----  https://app.powerbi.com/groups/me/reports/19b7db7b-e7be-4316-a1a1-629a92011b1d/4d7b977b7bb1612fe7b2?experience=power-bi

Student Performance Dashboard
Project Overview

The Student Performance Dashboard is developed using Power BI to analyze and visualize student performance data. The dashboard integrates academic scores, attendance records, and behavior information to generate meaningful insights for evaluation and decision-making.

The main objective of this project is to provide a structured and interactive analytical solution for monitoring overall student performance.

Dataset Information

The project is based on four datasets:

Students
Contains student details such as StudentID, Name, Class, and Section.

Scores
Contains subject-wise marks and maximum score values.

Attendance
Contains attendance status records (Present / Absent).

Behavior
Contains categorized behavior records for each student.

Data Modeling

The Students table is used as the Dimension table.

Scores, Attendance, and Behavior tables are treated as Fact tables.

Relationships are created using StudentID.

One-to-Many relationships with Single-direction cross filtering are implemented.

Proper data types are assigned to ensure accurate calculations.

Key DAX Measures

The following measures were created in Power BI:

Total Students – Distinct count of StudentID

Total Score – Sum of student scores

Total Max Score – Sum of maximum scores

Percentage Score – Total Score divided by Total Max Score

Average Score – Average of student marks

Attendance Percentage – Ratio of Present attendance records

Behavior Count – Total number of behavior entries

These measures allow dynamic KPI and visualization updates based on slicer selection.

Dashboard Visuals

The dashboard includes:

KPI Cards (Total Students, Percentage Score, Attendance Percentage)

Bar Chart (Subject-wise performance comparison)

Line Chart (Term-wise academic performance trend)

Treemap (Behavior distribution analysis)

Table Visual (Student-level performance details)

Slicers (Class, Section, Subject, Term)

Key Insights

Subject-wise academic trends can be analyzed effectively.

Attendance percentage impacts academic performance.

Behavioral patterns can be compared across different classes.

Interactive filtering allows customized analysis.
