# CodeAlpha_StudentGradeTracker

A beginner-friendly, console-based Java project for the CodeAlpha Java Programming internship task.

## Features
- Accepts multiple student names and marks.
- Validates student count and marks (0 to 100).
- Calculates each student's grade.
- Displays a summary report.
- Calculates average, highest, and lowest marks.
- Uses OOP (`Student` class), `ArrayList`, loops, methods, and input validation.

## Grade rules
- 90–100: A+
- 80–89: A
- 70–79: B
- 60–69: C
- 40–59: D
- 0–39: F

These grade ranges are sample rules and can be changed if your institute uses different rules.

## Requirements
- JDK 8 or later
- Eclipse IDE (or another Java IDE)

## Run in Eclipse
1. Extract the ZIP file.
2. Open Eclipse.
3. Select **File > Import > General > Existing Projects into Workspace**.
4. Choose the extracted `CodeAlpha_StudentGradeTracker` folder.
5. Click **Finish**.
6. Open `src/com/codealpha/studentgradetracker/StudentGradeTracker.java`.
7. Right-click the file and choose **Run As > Java Application**.

## Sample input
```text
Enter number of students: 3

Enter details for student 1:
Student name: Rahul
Marks (0-100): 80

Enter details for student 2:
Student name: Amit
Marks (0-100): 90

Enter details for student 3:
Student name: Priya
Marks (0-100): 70
```

## Sample report
```text
================ STUDENT REPORT ================
No.   Student Name             Marks      Grade
------------------------------------------------
1     Rahul                    80         A
2     Amit                     90         A+
3     Priya                    70         B
------------------------------------------------
Average marks : 80.00 / 100
Highest marks : 90 (Amit)
Lowest marks  : 70 (Priya)
Total students: 3
================================================
```

## GitHub repository name
`CodeAlpha_StudentGradeTracker`

## Suggested repository description
`A console-based Java Student Grade Tracker that calculates grades, average, highest and lowest marks using OOP and ArrayList.`

## Internship submission reminder
Before submitting, run the project yourself, understand the code, and follow the exact submission form and deadline provided by your internship coordinator.
