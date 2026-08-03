# OOT_A1-Stud_Info_sys
# Object Oriented Technology Labs - Assignment 1 - Student Information System

Student Information System Using Object-Oriented Programming (Java)
1. Introduction
The Student Information System is a Java application developed to demonstrate the basic concepts of Object-Oriented Programming (OOP). It represents a university with its schools, disciplines, programs, students, faculty, and courses. The project shows how different classes interact with each other using object-oriented principles.
________________________________________
2. OOP Concepts Used
1.	Abstraction
2.	Encapsulation
3.	Inheritance
4.	Polymorphism
5.	Object Composition
________________________________________
3. Classes Used
Class	Purpose
Person	Abstract class containing common details.
Student	Stores student information and course operations.
Faculty	Stores faculty information and manages attendance and grades.
University	Registers students and contains schools.
School	Contains disciplines.
Discipline	Contains academic programs.
Program	Connects students, faculty, and courses.
Course	Stores course details.
________________________________________
4. Relationships
•	University contains School.
•	School contains Discipline.
•	Discipline contains Program.
•	Program contains Student, Faculty, and Course.
•	Student enrolls in a Course.
•	Faculty teaches a Course.
________________________________________
6. Program Flow
1.	Create University.
2.	Create School.
3.	Link School to University.
4.	Create Discipline.
5.	Create Program.
6.	Create Faculty.
7.	Create Course.
8.	Create Student.
9.	Register Student.
10.	Student enrolls in a course.
11.	Faculty marks attendance.
12.	Faculty assigns grade.
13.	Student views CGPA.
14.	Student drops the course.
15.	Display roles using polymorphism.
________________________________________
7. Sample Output
   
C:\Users\Student\Desktop\Aditya Kamat\OOT\Student information System>java Main.java
Enter number of students: 2

Enter details of Student 1
Student ID: 2604
Name: Aditya Kamat
Semester: 1
CGPA: 9.1
Aditya Kamat registered successfully in Goa University
Aditya Kamat enrolled in Object Oriented Programming
Aditya Kamat enrolled in Database Management System
Attendance marked for Aditya Kamat
Grade A assigned to Aditya Kamat
CGPA: 9.1

Courses of Aditya Kamat:
- Object Oriented Programming
- Database Management System

--- Dropping a Course ---
Aditya Kamat dropped Database Management System

--- Courses after Dropping ---

Courses of Aditya Kamat:
- Object Oriented Programming

--- Enrolling in a New Course ---
Aditya Kamat enrolled in Artificial Intelligence

--- Courses after Enrolling in a New Course ---

Courses of Aditya Kamat:
- Object Oriented Programming
- Artificial Intelligence


Enter details of Student 2
Student ID: 2608
Name: Vaidehi Sinai Varde
Semester: 1
CGPA: 8.6
Vaidehi Sinai Varde registered successfully in Goa University
Vaidehi Sinai Varde enrolled in Object Oriented Programming
Vaidehi Sinai Varde enrolled in Database Management System
Attendance marked for Vaidehi Sinai Varde
Grade A assigned to Vaidehi Sinai Varde
CGPA: 8.6

Courses of Vaidehi Sinai Varde:
- Object Oriented Programming
- Database Management System

--- Dropping a Course ---
Vaidehi Sinai Varde dropped Database Management System

--- Courses after Dropping ---

Courses of Vaidehi Sinai Varde:
- Object Oriented Programming

--- Enrolling in a New Course ---
Vaidehi Sinai Varde enrolled in Artificial Intelligence

--- Courses after Enrolling in a New Course ---

Courses of Vaidehi Sinai Varde:
- Object Oriented Programming
- Artificial Intelligence



--- Polymorphism Demo ---
Aditya Kamat is a Student
Vaidehi Sinai Varde is a Student
Mr. Hanumant Redkar is a Faculty Member
________________________________________
8. Coding Guidelines
The following coding guidelines were followed while developing this project:
•	Use meaningful class names such as Student, Faculty, and University.
•	Keep variables and methods names simple and descriptive.
•	Declare data members as private to ensure encapsulation.
•	Use public methods to access or modify private data.
•	Use inheritance to avoid repeating common code.
•	Override methods using the @Override annotation where required.
•	Keep each class responsible for one main task.
•	Write proper indentation for better readability.
•	Add comments wherever necessary to explain important code.
•	Follow Java naming conventions:
o	Class names start with a capital letter (e.g., Student).
o	Variable and method names start with a small letter (e.g., studentId, displayRole()).
•	Keep methods short and easy to understand.
•	Avoid unnecessary code duplication.
10. Limitations
•	No database connectivity.
•	No graphical user interface.
•	Only one course can be enrolled at a time.
•	Data is not stored permanently.
________________________________________
11. Future Enhancements
•	Add database support.
•	Develop a GUI.
•	Allow multiple course enrollment.
•	Add login system for students and faculty.
•	Generate reports and attendance records.
________________________________________
12. Conclusion
This project successfully demonstrates the implementation of Object-Oriented Programming concepts in Java. It uses abstraction, encapsulation, inheritance, and polymorphism to model a simple Student Information system. The project provides a clear understanding of class relationships and serves as a good foundation for building larger Java applications.









________________________________________
Author: Aditya Timmappa Kamat
Class: MCA – I (Batch 2026-28)
Roll No.: 2604

