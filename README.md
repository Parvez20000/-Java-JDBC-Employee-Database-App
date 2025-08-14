# -Java-JDBC-Employee-Database-App
Employee Database App – Java JDBC
■ Objective
A simple Java application that connects to MySQL or PostgreSQL using JDBC and performs basic
CRUD (Create, Read, Update, Delete) operations on an Employee database.
■ Tools & Technologies
• Java (JDK 8 or later)
• MySQL / PostgreSQL
• JDBC Driver (Connector JAR)
• VS Code / Eclipse / IntelliJ IDEA
■ Features
1. Add Employee – Insert new employee details into the database.
2. View Employees – Fetch and display all employee records.
3. Update Employee – Modify existing employee details.
4. Delete Employee – Remove employee records by ID.
■■ Database Setup
Step 1: Create Database
SQL:
CREATE DATABASE employee_db;
Step 2: Create Table
SQL:
CREATE TABLE employees (
id INT PRIMARY KEY AUTO_INCREMENT,
name VARCHAR(50) NOT NULL,
department VARCHAR(50),
salary DOUBLE
);
■ JDBC Configuration
Download JDBC Driver:
• MySQL: https://dev.mysql.com/downloads/connector/j/
• PostgreSQL: https://jdbc.postgresql.org/download.html
Add the JAR file to your project’s classpath.
■ How to Run
1. Clone / Download the project.
2. Import into your IDE or open in VS Code.
3. Update DB Credentials in DBConnection.java:
