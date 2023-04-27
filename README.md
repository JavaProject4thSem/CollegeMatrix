# CollegeMatrix

## Problem Statement

The college management system currently in place is outdated, inefficient, and lacks the necessary features to fully support the needs of students, faculty, and staff. Various college management affairs have been digitalised after the pandemic but still many of the records are still maintained in registers which needed to be typed manually which is a tedious task. This results in a variety of issues such as difficulty in managing academic records, inefficient communication, cumbersome enrollment and registration processes, and limited access to key resources. As a result, there is a need for a modern and comprehensive college management system that can address these challenges and provide a seamless and efficient experience for all stakeholders.
## Our Proposed Solution

Our proposed college management website would include a range of features to help both students and faculty members of the college to manage their academic work more efficiently. Some of the key features of this website are as follows:

### Features
Student Section: This section contains three features and a panel showing the current students enrolled class, roll number, student name, course name, semester/year, the first feature is the roll generator where we can generate a unique roll number for a registered student not yet assigned a roll number, the second is view student , where you can view the student details that are currently enrolled in the college that are dynamically fetched from the live mysql server at the backend, then there is add student which opens up a form which after validating the details inserts it in the database.

Add Student and faculty: Newly admitted student as well as freshly recruited faculty can be added by the administrator in the database.

Add courses: Any kind of major or minor course proposed by the academic section can be added in the database and hence administration can offer the course to the students.

Subjects Section: Similar to the addition of courses further subjects in those courses can also be added. Already existing subjects or by fault added subjects can be removed also.

Assign Subjects: Administrator can assign a subject to an apt faculty to teach that particular subject to the students following a particular course. The distinction is ensured by the facility to add course code while assigning the subject.

Enter Marks: Faculties can reward marks for theory as well as practical exams after selecting the course, semester or year number and subject to fetch the student details of a particular class.

Marksheet Report: Similarly on the basis of course, sem no and subject faculties can view the marksheet of the student. This can be in three ways subject wise, class wise or student wise. There is an option to declare result also to make it visible to the students. 

Mark Attendance: Faculty can mark attendance of students upon selecting the date -> course name -> sem/year -> subject taught by them. 

Attendance Report: Faculty as well as the admin can view the attendance report of the student after selecting course-semester/year- subject.

Search: Any student, course or faculty along with it details can be display upon searching for it.

User: It contains the information of the application users like student, admin and faculty. 

Admin Profile: It mainly contains the name and mail id of the current admin which can be edited. Further it also contains the director name as well as id which also can be changed from here.

Logout: The current user can logout from the application through this option.

## Setup / Installation
#### Step 1 

Import this project into your IDE

#### Step 2
Install XAMPP control panel

Open it and then start the three servers viz : apache, tomcat, mysql server. This step basically opens up the server to come live and listen to client request on the localhost
#### Step 3

Go to phpmyadmin thorugh adminpanel in mysql server

#### Step 4

Create new Database and set name as 'collegedata' after that import 'collegedata.sql' file (Attached with this folder) in this database.

Database Connection

We have used following data for database connection

url="jdbc:mysql://localhost:3306/Collegedata";

user name="root"; password="";

####	How to Run

1.	Start Database Server

2.	Open "src/collegeapplication/chat/Server.java" and Run this file to start chat server

3.	Open "src/collegeapplication/login/LoginPageFrame.java" and Run this file to start application

Admin userid : admin

Admin password : admin

Faculty userid : Faculty id

Student Userid : cource-sem-rollnumber (IT-1-1001)


## Screenshots
![Screenshot (12)](https://user-images.githubusercontent.com/96315588/234847677-b04917ee-bd7d-4a53-9361-a818e691b10b.png)
![Screenshot (13)](https://user-images.githubusercontent.com/96315588/234833214-5b7b389f-6ff8-4098-85a2-2d4c65f08c2d.png)
![Screenshot (19)](https://user-images.githubusercontent.com/96315588/234833194-bd9f27f3-86bb-4f2c-90e9-dd170acbd03c.png)
![Screenshot (21)](https://user-images.githubusercontent.com/96315588/234833173-7a18bc99-3016-4155-9add-2e12994a7907.png)
![Screenshot (20)](https://user-images.githubusercontent.com/96315588/234833185-ef8f20c8-8d7e-48db-9987-18030626ad27.png)
![Screenshot (22)](https://user-images.githubusercontent.com/96315588/234833167-e5f7fac4-7c3b-4ced-ae88-cc68d2ca1829.png)
![Screenshot (29)](https://user-images.githubusercontent.com/96315588/234848820-05ca5a53-314c-47ab-b541-45e45bbe17d2.png)
![Screenshot (30)](https://user-images.githubusercontent.com/96315588/234835596-430f807a-da9a-4627-8234-28b0a99729f2.png)
![Screenshot (31)](https://user-images.githubusercontent.com/96315588/234835593-2309ae45-ccdc-4190-9c2b-7ec4f5d5a071.png)
![Screenshot (32)](https://user-images.githubusercontent.com/96315588/234835581-78886306-8847-4f73-a8fd-b321472aaed9.png)
![Screenshot (33)](https://user-images.githubusercontent.com/96315588/234835567-49b6ead8-ffe6-4778-bbd5-aa064a471d05.png)
![Screenshot (24)](https://user-images.githubusercontent.com/96315588/234833150-c58367b8-4a17-4bc0-ba37-be4ad23d5e3e.png)
![Screenshot (25)](https://user-images.githubusercontent.com/96315588/234833141-ddceb455-3a68-47fe-bdcb-61511b755011.png)
![Screenshot (26)](https://user-images.githubusercontent.com/96315588/234832667-2de94e10-6dbf-4aae-adc4-8a66931d613f.png)
![Screenshot (37)](https://user-images.githubusercontent.com/96315588/234832948-6261707f-5324-452e-8657-bfe638cd8665.png)
![Screenshot (38)](https://user-images.githubusercontent.com/96315588/234832932-5caa85aa-2b91-4a94-bc0e-3d46d33b3a4a.png)

## Contributors

### Abhishek Bharti 
Roll No:- 21124004    
Email id:- abhishekb.it.21@nitj.ac.in
### Apoorv Yash
Roll No:- 21124018     
Email id:- apoorvy.it.21@nitj.ac.in
### Jashan Sehgal
Roll No:- 21124044     
Email id:- jashans.it.21@nitj.ac.in
### Shreya Kumari
Roll No:- 21124102     
Email id:- shreyak.it.21@nitj.ac.in
