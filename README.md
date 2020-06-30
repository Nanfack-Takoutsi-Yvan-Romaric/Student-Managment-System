# Student-Managment-System

W3Professors.Com
Sample Synopsis
TITLE OF THE PROJECT
“ School
Management System ”
1 of 17W3Professors.Com
Sample Synopsis

#INTRODUCTION

The title of the project is “School Management system”. This project will handle whole
the activities of the school. SMS has most of the facilities that a modern school requires to
computerize its day-to-day jobs. It provides facilities to keep the records of student, fees,
teaching and non-teaching staff with all their required details along with all required
transaction handling. It has facilities to generate various types of reports, which are required
by the management during normal business operations to operate the business effectively.
2 of 17W3Professors.Com
Sample Synopsis
OBJECTIVES
This project is based on the RDBMS technology; the main objective of this project is
to computerize the manual system & reduce the time consumption.
In other words we can say that our project has the following objectives:-
 Make all the system computerize
 Reduce time consumption
 Reduce error scope
 All system managements are automated
 Centralized database management
 Easy operations for operator of the system
 No paper work requirement
3 of 17W3Professors.Com
Sample Synopsis
PROJECT CATEGORY
This project as title “School management system” is comes under the Relational Database
Management System (RDBMS). This application is developed with the help of Visual basic 6.0 and
Oracle 8. This application can also be run on the network environment so it can be said as network
application.
TOOLS/PLATFORM
This project is developed using the tools, which are most suited for development of the
Application Package. These tools are as follows: -
1. Visual Basic 6.0 (For front end)
2. Oracle 8 (For Database Storage as Back end)
4 of 17W3Professors.Com
Sample Synopsis
HARDWARE & SOFTWARE REQUIREMENT
HARDWARE:
Processor Pentium-II or higher
Processor Speed 533 MHZ
Hard Disk Space 20 GB (min.)
Ram Memory 32 MB (64 MB recommended)
SOFTWARE:
Operating System Windows 95/98/NT/2000
Database Server ORACLE 8
Front end Visual Basic 6.0
5 of 17W3Professors.Com
Sample Synopsis
SYSTEM DESIGN
System Design is the solution to the creation of a new system. This is the important aspect
made up of several steps. The complete, efficient and successful system should provide the following
in succession: -
 From where should we start
 Where we have to go
 Where should we stop
If the project is to be successful, we will need answer these question. The answer of these
questions is schema manner and is known as system design.
A systematic manner will be followed so as to achieve beneficial result at the end. It involves
starting with a vague idea and ultimately developing it up into a useful system. The design phase is
transition from a user oriented to a document oriented to the programmers.
Software report can be broken into a series of steps starting with the basic ideas and ending
with the finished project.
6 of 17W3Professors.Com
Sample Synopsis
The steps for the successful project are as follows: -
 We should define problem completely and the goals should be known before our destination
 In the next step, we should specify inputs and outputs of our interest
 Then the structure of various database should be designed which will be used during the
programming
 Next, we should design our programs of user friendly nature and always provide a way to the
user to read back the origin if he/she find any complex problem at any stage
 We should know the function of each and every program which will leads us to or helps us to
read at the specified goal.
 Then we write these individual programs which later on joining solve our problem
 Next step involve then testing of these programs and correction – if necessary
 At last, linking all the programs in a well-specified manner and combining in the form of a
menu, submenu etc. will be our defined problem.
Out of these defined steps, few of the major steps will respect to Project
“School Management System”
7 of 17W3Professors.Com
Sample Synopsis
DATA FLOW DIAGRAMS (DFD’S)
The DFD was first developed by Larry Constiane as a way of expressing system in a graphical
form. A DFD, also known as Bubble Chart, has a purpose of clarifying system requirement and
identifying major transformation that will become the programs in the system design.
DFD SYMBOLS
1. A SQUARE defines a source or destination of system data
2.
An ARROW identifies data flow or data in motion. It is a pipeline through which
information flow.
3. A CIRCLE or a BUBBLE (Some people use an over bubble) represents a process transforms
in coming data flow into outgoing data flow.
4. An OPEN RECTANGLE is a data store or data at rest or a temporary rest repository of data.
Note that a DFD describe what data flow (logical) rather than they are processed, so it does not
depend on hardware, software and data structure or file organization.
8 of 17W3Professors.Com
Sample Synopsis
PROCESSING OF SMS
Student
School
Mgmt
Management
Committee
A School has to deal with two external entities: -
 The School
 The management Committee
9 of 17W3Professors.Com
Sample Synopsis
School
Management
System
Student
Admission
Staff
School
Management
System
Staff
10 of 17W3Professors.Com
Sample Synopsis
DATABASE DESIGN
Database Design in most important in any project. We are using the following table to store
the information related to staff of school
1. STAFF
Field Name NULL Type
EMPNO Not Null NUMBER (5)
EMPNAME VARCAHR (30)
ADDRESS VARCHAR (30)
CITY VARCAHR (15)
PIN VARCAHR (6)
STATE VARCAHR (15)
PHONE VARCAHR (15)
MOBILE VARCAHR (13)
EMAIL VARCAHR (30)
SEX VARCAHR (1)
M_STATUS VARCAHR (15)
DOB DATE
DOJ DATE
DEPT VARCAHR (30)
NATURE_OF_JOB VARCAHR (10)
BASIC_PAY NUMBER (10,2)
11 of 17W3Professors.Com
Sample Synopsis
2. STUDENT
Field Name NULL Type
REGNO NOT NULL NUMBER (5)
ROLLNO NOTNULL NUMBER (5)
CLASS VARCHAR (4)
NAME VARCHAR (25)
FNAME VARCHAR (25)
MNAME VARCHAR (25)
DOB DATE
DOR DATE
ADDRESS VARCHAR (30)
CITY VARCHAR (15)
STATE VARCHAR (15)
PIN VARCHAR (6)
PHONE VARCHAR (15)
3. FEE
Field Name NULL Type
REGNO NOT NULL NUMBER (5)
ROLLNO NOTNULL NUMBER (5)
CLASS VARCHAR (4)
FEEDEP NUMBER (5)
DEPDATE DATE
FINE NUMBER (3)
12 of 17W3Professors.Com
Sample Synopsis
4 RESULTS
Field Name NULL Type
REGNO NOT NULL NUMBER (5)
SUBJECT_NAME VARCHAR (15)
MAX_MARKS NUMBER (3)
PASS_MARKS NUMBER (3)
MARKS_OBT NUMBER (3)
RESULT VARCHAR (4)
13 of 17W3Professors.Com
Sample Synopsis
MODULES USED IN THE PROJECT
This project includes the following modules for development of the project. These are as
follows: -
1. SPLASH FORM
This is a first form that displays the welcome screen for the user and also shows the
information of developer or version etc.
2. LOGIN FORM
This form shows the Login name and password when user enter a valid user name and
password then he/she can operate the application.
3. MAIN FORM
This form is a menu-based form that displays the menu for operation of the application. It
includes various options for staff, student, fees and report related option.
4. STUDENT FORM
This form provides the option to add, modify, delete or find the information of a student who
seeks the admission in the school.
5. STAFF FORM
This forms provides the option to add, delete, search and delete the information of staff (either
teaching or non-teaching) that is working in the school.
6. FEE FORM
This form provides the option to the user of the system to add, delete, modify and search the
information of the fee deposited by the student.
7. RESULT FORM
14 of 17W3Professors.Com
Sample Synopsis
This form displays the options for the user to add, delete and modify the details of student
related to the marks.
8. REPORT FORM
With the help of this option from menu user of the system can see or take the print out of
various reports provided by the system.
9. GOODBYE FORM
This form is activating when user select the exit option from menu or close the application.
This form shows the good-bye message to the user and also say thanks to the user for using
this application
15 of 17W3Professors.Com
Sample Synopsis
.
NAME OF REPORTS
Following are the reports names that are generated by the Project for the management of school or
staff members of the school.
1. Details of Teaching staff
2. Details of non-teaching staff
3. Class wise detail of students
4. Date wise detail of students based on date of admission
5. Detail of student according to name wise
6. Teacher report based on the Date of joining
16 of 17W3Professors.Com
Sample Synopsis
FUTURE SCOPE OF THE PROJECT
Nothing is perfect in this world. So, we are also no exception. Although, we have tried our
best to present the information effectively, yet, there can be further enhancement in the Application.
We have taken care of all the critical aspects, which need to take care of during the development of
the Project.
Like the things this project also has some limitations and can further be enhances by
some one, because there are certain drawbacks that do not permit the system to be 100%
accurate.
17 of 17
