<h1>ER Model, Relational Model & SQL</h1>

<h2>Description</h2>
This project is a sequence of SQL statements for creating tables, inserting records, and committing the changes.
The code starts by dropping existing tables: STUDENT, DEPARTMENT, COURSE, SECTION, and STUD_SECT.
It then proceeds to create the following tables:

- STUDENT: This table has several columns representing student information such as student number, HKID, cohort, sex, birth date, names, address, contact information, degree program, major, and minor codes.
- DEPARTMENT: This table has columns for grade, lowest salary (LOSAL), and highest salary (HISAL).
- COURSE: This table has columns representing employee information such as employee number (EMPNO), employee name (ENAME), job title (JOB), manager number (MGR), hire date (HIREDATE), salary (SAL), commission (COMM), and student number (STUDENTNO).
- SECTION: This table has the same structure as the COURSE table.
- STUD_SECT: This table also has the same structure as the COURSE table.

The code then proceeds to insert records into the STUDENT, DEPARTMENT, and COURSE tables using the INSERT INTO statements.
The SECTION and STUD_SECT tables are left empty as there are no corresponding INSERT INTO statements.
Finally, the COMMIT statement is used to save the changes made to the database.
<br />

<h2>Languages and Utilities Used</h2>

- <b>SQL</b>

<h2>Design Model:</h2>

<p align="center">
<img src="https://imgur.com/NyLFb8c.png" height="80%" width="80%" alt="AOS & JS"/>
<br />
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
