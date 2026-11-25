# 📋 Attendance Management System
### Java (JSP/Servlet) + MySQL Web Application

> ⚠️ **DISCLAIMER:** This is a **personal learning and portfolio project**. It is a web-based attendance tracking system built with Java (JSP/Servlet) and MySQL for educational purposes. All student data, credentials, and attendance records in the bundled SQL file are **fictional sample data**. This project is **NOT** an official attendance system of any institution, and it is not hardened for production use without security review.

A full-stack attendance management system built with Java (JSP, Servlet), MySQL, and Apache NetBeans 21. It enables administrators and faculty to authenticate, manage student records, mark and view attendance, and generate class-wide or individual reports — all through a browser-based interface served by Tomcat.

![Version](https://img.shields.io/badge/Version-1.0.0-ED8B00)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-F4B400)
![Stack](https://img.shields.io/badge/Stack-JSP%20%7C%20Servlet%20%7C%20MySQL-2D6A4F)

---

## 🔗 Links

- **Source Code:** [github.com/Ashish22Gupta/Attendance-Management-System](https://github.com/Ashish22Gupta/Attendance-Management-System)

> 💡 *No live demo — requires a local Java + MySQL + Tomcat environment. Follow the setup steps below.*

---

## ✨ Implemented Features

### 🔐 User Authentication
- **Secure Login** — Administrators and faculty members log in with credentials stored in the database.
- **Session Management** — Authenticated sessions are tracked via the servlet container, restricting dashboard access to logged-in users only.

### 🎓 Student Management
- **Add Students** — Register new students with identifying details.
- **Update Students** — Edit existing student records.
- **Delete Students** — Remove student entries from the system.

### ✅ Attendance Tracking
- **Mark Attendance** — Record attendance for students on a given day/period.
- **View Attendance** — Browse historical attendance data by student or class.

### 📊 Reporting
- **Individual Reports** — Generate attendance reports for a single student.
- **Class-Wide Reports** — Produce aggregate reports across an entire class.
- **Exportable Output** — Reports can be exported for offline record-keeping.

### 🗄️ Database Integration
- **MySQL Backend** — All data (users, students, attendance records) is persisted in MySQL.
- **Bundled SQL Schema** — A ready-to-import `.sql` file is included in the `DATABASE` folder for instant setup.

### 🎨 Frontend
- **HTML5 / CSS3 / JavaScript** — Clean, form-based UI for all management operations.
- **JSP Server-Side Rendering** — Dynamic pages rendered via JSP on Apache Tomcat.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Java (JSP / Servlet)** | Server-side rendering and request handling |
| **MySQL** | Relational database for users, students, and attendance |
| **MySQL JDBC Driver** | Java–MySQL connectivity |
| **HTML5 / CSS3** | UI structure and styling |
| **JavaScript** | Client-side interactivity and validation |
| **Apache NetBeans IDE 21** | Development environment |
| **Apache Tomcat** | Servlet container / application server |

---

## 📁 Project Structure

```text
Attendance-Management-System/
├── DATABASE/
│   └── attendance management system.sql    # MySQL schema + sample data
│
├── src/
│   └── java/                               # Servlets & backend logic
│
├── web/ (or WebContent/)
│   ├── *.jsp                               # JSP pages (login, dashboard, reports)
│   ├── css/                                # Stylesheets
│   └── js/                                 # Client-side scripts
│
├── WEB-INF/
│   └── web.xml                             # Servlet mappings & config
│
└── nbproject/                              # NetBeans project metadata
