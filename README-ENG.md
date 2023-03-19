# School Management System [![gr](https://img.shields.io/badge/lang-gr-blue.svg)](https://github.com/cbalampa/School-Management-System/blob/main/README.md) [![eng](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/cbalampa/School-Management-System/blob/main/README-ENG.md)

Contents
=================
* [App Description](#app-description)
* [Technologies](#technologies)
* [Database](#database)
* [Setup](#setup)
* [Features](#features)
* [Preview](#preview)

## App Description
School management system that uses a relational database and manages information regarding the main entities of a school. Through this system, administrators have the ability to perform actions such as adding students, assign courses, updating grades, etc. 

## Technologies
The following technologies were used to create the project:
- Java
- JDBC
- PL/SQL

## Setup
You can try this project by simply downloading the files you will find in the link below:
[https://drive.google.com/drive/folders/1pJ5gunGfKSx0DVSlSLpo50qVZFlNLviE?usp=sharing](https://drive.google.com/drive/folders/1pJ5gunGfKSx0DVSlSLpo50qVZFlNLviE?usp=sharing)

When download is finished, double-click the executable jar file named "TBD2021", which is located inside the "dist" folder. Further information on successfully connection to the database can be found in its README file.

## Database
Consists of eight tables that are related to each other using foreign keys as shown in the image below.

![Database Diagram](https://user-images.githubusercontent.com/73292440/124173684-094de380-dab4-11eb-8797-acdd8573c0d5.png)


## Features
Manage Students
- Insert a student to database
- Edit/update student's information
- Delete a student from database
- Search for a student (dynamic search bar)
 
Manage Teachers
- Insert a teacher to database
- Edit/update teacher's information
- Delete a teacher from database
- Search for a teacher (dynamic search bar)

Manage Classrooms
- Create a new class
- Delete a class
- Add students to classes
- Change student's class

Manage Courses
- Insert a course to database
- Delete a course from database
- Assign a course to a teacher 
- Change teacher's course
- Remove teacher-course relationship

Manage Grades
- Change student's grades
- Bonus: Details (best student, top five students)


## Preview
<p align="center">
<img src="https://user-images.githubusercontent.com/73292440/124302250-9dc64d80-db69-11eb-9cbc-7721ea3faeb0.gif" alt="drawing" width="600"/>
</p>



