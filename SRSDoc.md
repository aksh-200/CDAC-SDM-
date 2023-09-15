# Online assessment for CDAC Exam

## Document:
System Requirement Online assessment for CDAC Exam

## Title:
Online Assessment Portal

## Team: 
Student,Faculty,Cdac Center Manager,CDAC Authority,CDAC Center Director

## Objective (Purpose):
The online exam portal will be used to conduct various discipline exam at a time.Also various institute will be part of this system.The result will be declared automatically after submitting the exam.It will be a proctored exam and user facial detection will be detected.Conducting exams online will eliminate the need of costly logistics and paper work,reduce  cost and time saving.Authority will have ability to make changes according to them.

## Scope:
This system allows student to make changes in the options they'll choose.Also some question will be paragraph based so they can type there answer overthere.If by chance theres a powercut or internet connectivity issue the student can restart the exam from where he/she have left.Username and password will be generated for every faculty members and for students.The respective authority can watch how many student had logged in for the exam and has permission to revoke a student from exam for unfair means.

## Definitions:
	
	Interface
	Navigation
	SS

## Functional Requirements:

First the student has to do his biometrics at the center with the help off cdac officals.The CDAC officials will cross verify the student details with the online details which he/she uploaded during registration.After Biometrics they will get alloted to respective PCs from the ADMIN system.
The system will generate temporary LoginID and key for that particular student.Student on his interface can see how much time is left for exam to start.The student will get a message on his screen to start the exam. 
After confirming he/she can read instructions for the exam and can sign terms and conditons of the exam. 
After accepting the terms and conditions he/she will be redirected to exam window where they can see timer,question panel,answered/unanswered/bookmarked questions,and can navigate through the questions.

The ADMIN has authority to start the exam at the given time or he can schedule that exam for a period of time.The admin can see how many students are present for the exam and he can see how many of them had logged in for the exam.The Also the test is submitted automatically to the local server which will later be pushed to CDAC Center.The Admin can watch how many student had logged in for the exam and has permission to revoke a student from exam for unfair means.

Faculty can create, upload and make changes to the exam paper directory whenever they want
The portal will be closed 15 days before the exam day.

## NonFunctional Requirement:

### Security
Each student can access to alloted PC using the credentials given to them.
System will provide access to  the questions when time starts.Chrome or Mozilla Firefox should be used(Updated versions) 
operations using Role based security (Authorization) (Permissions based on Role)
Proctoring can be done even by taking SS of the screen
System will automatically log of  all student after completion of exam.
System will block operations for inactive  student and would redirect for authentication.
Various data encryptions will be used.
System  will internally maintain secure communiction channel between Servers 
User proper firewall to protect servers from out side fishing, velnerable attacks.


### Reliability
The system will backup the exam when there's powercut or any other kindoff interupptions and recover it in short time duration to keep system operational
During peak hours system will maintain same user experaince by managing load balacning .

### Availability
uptime:   The exam day
	
### Maintainability:
The system data persistence will be managed using commercial database software.
To handle server capabilities, a ready-made web server will be deployed to host an online shopping site (Web Site).
Utilizing the administrative capabilities given by servers, the IT operations team may quickly setup and monitor the system.
System isolation in production, testing, and development will be maintained in a distinct environment.

### Portablility:
PDA: Portable Device Application
System will provide portable User Interface ( HTML, CSS, JS) through  users will be able to access online shopping portal.
System can be deployed to single server, multi server, to any OS, Cloud (Azure or AWS or GCP)

### Accessibility:
only registered student will be able to give the exam.
CDAC Authority can reject or approve students canditature on unfair means .

### Durability:
The duration for particular login will be 1hr15min.

### Efficiency:
on exam day, maximum number of users  will be logged in, view exam and give some/same responses at a time.
System will be able to manage all responses with isolation.

### Modularity:
System will designed and developed to record every respone of a student
These modules will be loosely coupled and highly cohesive.
	
### Scalability:
System will be able  to  run at a wide range at given test time.

### Safety:	
the exam will be proctored and firewall should be active.
Also the student will not be able to connect to external websites.