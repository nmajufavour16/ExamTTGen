# Automated Exam Timetable Generator
Core Idea:
Generate exam schedules automatically while avoiding conflicts.

Example Data

Courses:
MTH101
PHY101
CSC101
ENG101

Students:
Student A:
MTH101
PHY101

Student B:
PHY101
CSC101

Student C:
CSC101
ENG101
Problem

You cannot schedule:
MTH101
PHY101
at the same time because Student A takes both.

Likewise:
PHY101
CSC101
cannot clash.

*Conflict Detection*
Program must discover:
MTH101 ↔ PHY101
PHY101 ↔ CSC101
CSC101 ↔ ENG101

Schedule Generation
Available slots:
Monday Morning
Monday Afternoon
Tuesday Morning
Tuesday Afternoon

Program assigns:
MTH101 -> Monday Morning
CSC101 -> Monday Morning
PHY101 -> Monday Afternoon
ENG101 -> Monday Afternoon
No student has two exams simultaneously.

*User Features*
1. Add Course
2. Register Students
3. Generate Timetable
4. View Timetable
5. Detect Conflicts

Timetable Report
Example:
Monday Morning
MTH101
CSC101

Monday Afternoon
PHY101
ENG101