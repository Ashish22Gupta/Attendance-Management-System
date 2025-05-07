# Attendance-Management-System
Technology: Html, Css, Js, Java, MySQL
An Attendance Management System developed using Java (JSP, Servlet), MySQL, and Apache NetBeans IDE 21. This application facilitates efficient tracking and management of student attendance records.

# Features
User Authentication: Secure login for administrators and faculty members.
Student Management: Add, update, and delete student records.
Attendance Tracking: Mark and view attendance for students.
Reporting: Generate attendance reports for individual students or entire classes.
Database Integration: Seamless integration with MySQL for data storage.

# Prerequisites
Before setting up the project, ensure the following software are installed on your system:
Apache NetBeans IDE 21
XAMPP Control Panel (includes Apache and MySQL)
MySQL JDBC Driver

# Setup Instructions
Follow these steps to set up and run the project:
1. Clone the Repository
Copy
Edit
Alternatively, download the ZIP file and extract it to your desired location.

2. Start XAMPP Services
Open the XAMPP Control Panel.
Start the Apache and MySQL services.

3. Set Up the Database
Open your browser and navigate to http://localhost/phpmyadmin.
Click on the Databases tab.
Create a new database named attendance management system.
Click on the Import tab.
Choose the attendance management system.sql file located in the DATABASE folder of the project.
Click Go to import the database schema and data.

4. Configure Apache NetBeans IDE
Launch Apache NetBeans IDE 21.
Go to File > Open Project.
Navigate to the extracted project folder and open it.
Right-click on the project in the Projects pane and select Properties.
Under Libraries, add the MySQL JDBC Driver:
Click Add JAR/Folder.
Navigate to the location of the downloaded MySQL JDBC Driver JAR file and add it.
Under Run, ensure the server is set to Apache Tomcat (configure if not already set).

5. Build and Run the Project
Right-click on the project and select Clean and Build.
After the build is successful, right-click on the project and select Run.
The application should open in your default browser at http://localhost:8080/Attendance Management System.

# Usage
Login: Use the default credentials provided in the README or as set in the database.
Dashboard: Navigate through the dashboard to manage students and attendance records.
Reports: Generate and export attendance reports as needed.

# Troubleshooting
Port Conflicts: Ensure that ports 80 (Apache) and 3306 (MySQL) are not being used by other applications.
Database Connection Issues: Verify that the database name, username, and password in the project's database configuration match your MySQL settings.
Missing JDBC Driver: Ensure the MySQL JDBC Driver is correctly added to the project's libraries.
