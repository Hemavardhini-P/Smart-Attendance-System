# Smart Attendance System

## 📖 Overview

The Smart Attendance System is a web-based application developed to automate student attendance tracking and eliminate manual record-keeping. The system provides a secure and efficient platform for managing students, staff, and attendance records while improving accuracy, transparency, and administrative efficiency in educational institutions.

## 🚀 Features

* Secure User Authentication and Authorization
* Student Management Module
* Staff Management Module
* Attendance Management System
* Digital Attendance Marking
* Attendance Report Generation
* Student Attendance Tracking
* CRUD Operations (Create, Read, Update, Delete)
* Database Integration with MySQL
* Responsive User Interface using Bootstrap
* Secure Data Storage and Management

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* PHP

### Database

* MySQL

## 📂 Project Modules

### Student Management

* Add, update, view, and delete student records.
* Manage student profiles and information.

### Staff Management

* Maintain staff records.
* Assign attendance responsibilities.

### Attendance Management

* Mark attendance digitally.
* Store attendance records securely.
* Update and manage attendance details.

### Reports

* Generate attendance reports instantly.
* View attendance statistics and records.

### Authentication

* Secure login system.
* Role-based access control for staff and students.

## 📁 Project Structure

```text
Smart-Attendance-System/
│
├── css/
├── js/
├── images/
├── includes/
├── database/
│   └── attendance_db.sql
├── admin/
├── student/
├── staff/
├── index.php
├── login.php
├── dashboard.php
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/smart-attendance-system.git
```

### 2. Move Project to Server Directory

For XAMPP:

```text
xampp/htdocs/
```

For WAMP:

```text
wamp/www/
```

### 3. Create Database

* Open phpMyAdmin.
* Create a database named:

```sql
attendance_db
```

* Import the provided SQL file.

### 4. Configure Database Connection

Update database credentials in the configuration file:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "attendance_db";
```

### 5. Run the Application

Start Apache and MySQL from XAMPP/WAMP and open:

```text
http://localhost/Smart-Attendance-System
```

## 🔐 Security Features

* User Authentication
* Session Management
* Secure Database Connectivity
* Role-Based Access Control
* Protected Attendance Records

## 📈 Benefits

* Eliminates manual attendance records.
* Reduces administrative workload.
* Improves attendance tracking accuracy.
* Provides transparency for students and staff.
* Generates reports instantly.
* Ensures secure data management.

## 🎯 Future Enhancements

* QR Code-Based Attendance
* Face Recognition Attendance
* Email Notifications
* Mobile Application Support
* Attendance Analytics Dashboard
* Cloud Deployment

## 📸 Screenshots

Add screenshots of the application here.

### Login Page

![Login Page](screenshots/login.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Attendance Management

![Attendance Management](screenshots/attendance.png)

## 👨‍💻 Project Information

**Project Title:** Smart Attendance System

**Duration:** December 2025

**Technology Stack:** PHP, MySQL, HTML, CSS, JavaScript, Bootstrap

## 📄 License

This project is developed for educational and learning purposes.

