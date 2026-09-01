# Attendance-monitoring-system
AI-Based Attendance Monitoring System with Email Notifications

This project involves developing an automated attendance monitoring system that helps teachers manage student attendance efficiently. The system allows attendance to be recorded digitally and automatically sends email notifications to students or parents regarding attendance updates.

The goal is to reduce manual attendance management, maintain accurate attendance records, and provide timely notifications through email.

Key Features

- Student registration and management
- Teacher/admin login
- Digital attendance marking
- Automatic attendance record storage
- Email notifications for attendance
- Attendance percentage calculation
- Daily and monthly attendance reports
- Student-wise attendance tracking
- Low-attendance alerts
- Database-based attendance management
- Simple and user-friendly interface

Technology Used

Programming Language

- Python

Libraries & Frameworks

- Flask
- Pandas
- NumPy
- Matplotlib
- SMTP / Python Email Library

Database

- MySQL / SQLite

Frontend

- HTML
- CSS
- JavaScript
- Bootstrap

System Workflow

1. Admin/teacher logs into the system.
2. Student details are registered in the database.
3. Teacher selects the class and subject.
4. Attendance is marked as Present or Absent.
5. Attendance is automatically stored in the database.
6. The system calculates the student's attendance percentage.
7. An email notification is sent to the student's registered email address.
8. If attendance falls below a predefined percentage, a low-attendance alert is generated.
9. Teachers/admins can view and generate attendance reports.

Email Notification System

The system uses email services to automatically notify students about their attendance.

Example notifications include:

- Attendance marked for the day
- Student marked absent
- Low attendance warning
- Attendance percentage update

Example:

Subject: Attendance Notification

Dear Student,

Your attendance has been recorded for today's class.

Subject: Data Structures
Date: 01-09-2026
Status: Present
Attendance Percentage: 82%

Regards,
Attendance Monitoring System

Database

The system stores information such as:

- Student ID
- Student Name
- Roll Number
- Email Address
- Subject
- Date
- Attendance Status
- Attendance Percentage

Example:

Student ID| Name| Subject| Date| Status| Email
101| Student 1| Data Structures| 01-09-2026| Present| student1@email.com
102| Student 2| Data Structures| 01-09-2026| Absent| student2@email.com

Project Structure

Attendance-Monitoring-System/
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   ├── attendance.html
│   └── report.html
│
├── static/
│   ├── css/
│   └── js/
│
├── app.py
├── database.py
├── attendance.py
├── email_service.py
├── requirements.txt
└── README.md

Main Modules

1. User Authentication

Provides secure login for teachers and administrators.

2. Student Management

Allows the administrator to add, update, and manage student information.

3. Attendance Management

Teachers can mark and update student attendance digitally.

4. Email Notification

Automatically sends attendance-related notifications to registered email addresses.

5. Attendance Calculation

Calculates attendance percentages based on the student's attendance records.

6. Reports

Provides daily, monthly, and student-wise attendance reports.

AI/ML Component

If the project includes an AI/ML component, machine learning can be used to analyze historical attendance data and identify students who may be at risk of having low attendance.

The system can use factors such as:

- Previous attendance percentage
- Number of absences
- Attendance trends
- Subject-wise attendance

The model can classify students into categories such as:

- Good Attendance
- Average Attendance
- Low Attendance Risk

The system can then send an email alert to students who are predicted to have attendance problems.

Advantages

- Reduces manual attendance management
- Saves teachers' time
- Maintains centralized attendance records
- Automatically sends email notifications
- Helps students track their attendance
- Identifies low-attendance students
- Generates attendance reports
- Reduces errors in attendance calculations

Future Improvements

- Mobile application
- Parent email notifications
- SMS notifications
- AI-based attendance prediction
- Cloud database
- Student dashboard
- Teacher dashboard
- Automatic timetable integration
- College ERP integration
- Advanced attendance analytics

Installation

Clone the repository:

git clone <your-github-repository-link>
cd Attendance-Monitoring-System

Install the required libraries:

pip install -r requirements.txt

Run the application:

python app.py


Connect Me

LinkedIn:

GitHub: 