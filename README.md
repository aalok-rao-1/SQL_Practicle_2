In this SQL program i create a college database with four tables: Department, Student, Course, and Enrollment.
The Department table stores department names and IDs.
The Student table stores student details like roll number, name, email, Aadhaar number, and department. 
The Course table stores course names and their departments.
The Enrollment table connects students with courses and stores their semester and grade. 
Primary keys uniquely identify records, while foreign keys connect related tables. 
The CHECK constraint ensures semesters are between 1 and 8. 
For example, student 105 can enroll in multiple courses, but cannot enroll in the same course twice in the same semester.
