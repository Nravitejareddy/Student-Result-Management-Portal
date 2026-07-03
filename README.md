# 🎓 Student Result Management Portal
### Web-based Academic Result Management System

![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/Frontend-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Style-CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=white)
![AJAX](https://img.shields.io/badge/AJAX-Asynchronous-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

The **Student Result Management Portal (SRMS)** is a web-based academic management system developed using **PHP** and **MySQL**. It enables educational institutions to efficiently manage student records, subjects, classes, examination results, and notices through a secure administrator portal while allowing students to access their academic results using their Roll ID.

---

# 📂 Repository Structure

```text
Student-Result-Management-Portal/
│
├── DB/                     # Database schema
├── css/                    # Stylesheets
├── dompdf/                 # PDF generation library
├── fonts/                  # Font assets
├── images/                 # Image assets
├── includes/               # Common PHP components
├── js/                     # JavaScript files
├── saas/                   # SCSS source files
│
├── index.php               # Home page
├── admin/                  # Administrator module
├── student/                # Student module
├── login.php               # Authentication
├── logout.php
├── README.md
└── ...
```

---

# 🏗 System Architecture

```text
                ┌──────────────────────┐
                │      Student         │
                └──────────┬───────────┘
                           │
                    Result Search
                           │
                           ▼
               PHP Web Application
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        ▼                  ▼                  ▼
 Admin Dashboard      Result Engine      Notice Module
        │                  │
        └──────────────┬───┘
                       ▼
                 MySQL Database
```

---

# ✨ Key Highlights

- 🎓 Student Result Management
- 👨‍🏫 Administrator Dashboard
- 📚 Class & Subject Management
- 📝 Examination Result Publishing
- 🔍 Student Result Search
- 📢 Notice Board Management
- 🔐 Secure Administrator Login
- 📄 PDF Report Generation
- ⚡ Responsive Web Interface

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Backend | PHP |
| Database | MySQL |
| Frontend | HTML5 • CSS3 • JavaScript |
| Dynamic UI | AJAX • jQuery |
| PDF Generation | DOMPDF |
| Local Server | XAMPP • WAMP • MAMP • LAMP |
| Browser Support | Chrome • Firefox • Opera • Edge |

---

# 📱 Modules

## 👨‍💼 Administrator Module

> 📖 **Description**  
> The administrator portal provides complete control over student records, examination results, classes, subjects, notices, and system administration through a secure authentication system.

> 🛠 **Features**
>
> • Dashboard  
> • Student Registration & Management  
> • Class Management  
> • Subject Management  
> • Subject Combination Management  
> • Result Declaration & Editing  
> • Notice Management  
> • Password Management

---

## 👨‍🎓 Student Module

> 📖 **Description**  
> Students can securely search and view their academic results using their Roll ID without requiring administrative access.

> 🛠 **Features**
>
> • Result Search  
> • View Academic Results  
> • Notice Board Access

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/Nravitejareddy/Student-Result-Management-Portal.git

cd Student-Result-Management-Portal
```

---

## 2. Install Project

Copy the project folder into your local web server directory.

Example (XAMPP):

```text
C:\xampp\htdocs\
```

Final location:

```text
C:\xampp\htdocs\Student-Result-Management-Portal
```

---

## 3. Start Services

Launch **XAMPP Control Panel** and start:

```text
Apache
MySQL
```

---

## 4. Database Setup

Open phpMyAdmin:

```text
http://localhost/phpmyadmin
```

Create a database named:

```text
srms
```

Import:

```text
DB/srms.sql
```

---

## 5. Run the Application

Open your browser:

```text
http://localhost/Student-Result-Management-Portal/
```

---

# 🔑 Default Credentials

## 👨‍💼 Administrator

```text
Username : admin
Password : Test@123
```

---

## 👨‍🎓 Sample Student

```text
Student Name : Anuj Kumar
Roll ID      : 10861
Class        : Fourth (C)
```

---

# 📸 Screenshots

> Screenshots can be added here.

- 🏠 Home Page
- 👨‍💼 Administrator Dashboard
- 🔍 Student Result Search
- 📄 Student Result Page

---

# 📈 Future Enhancements

- 📧 Email Notifications
- 📱 Mobile Responsive Dashboard
- 📊 Advanced Result Analytics
- 📥 Excel & PDF Export
- ☁️ Cloud Deployment
- 🔐 Two-Factor Authentication
- 👨‍🏫 Faculty Portal
- 📚 Semester-wise Performance Tracking

---

# 📄 License

This project was developed as an academic project and is maintained for educational and portfolio purposes.

---

# 👨‍💻 Author

**Ravi Teja Reddy N**

Computer Science & Engineering Graduate

🐙 GitHub: <https://github.com/Nravitejareddy>

---

# ⭐ Project Status

> ✅ **Completed** — Developed as an academic web application demonstrating PHP, MySQL, CRUD operations, authentication, and database-driven result management.

---

> **Student Result Management Portal — Simplifying Academic Result Administration through Web Technology.**
