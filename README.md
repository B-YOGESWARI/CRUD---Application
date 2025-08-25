# CRUD---Application

Java CRUD application with MySQL connection.

This is a CRUD (Create, Read, Update, Delete) Application built using Java and MySQL.

The project demonstrates how to perform basic database operations in a structured and beginner-friendly way.

CRUD operations are the backbone of most real-world applications, whether it’s managing user data, employee records, or product inventories.

This project helped me strengthen my Java programming and database management concepts.

**Features**:

Create ➝ Add new records into the database.
Read ➝ Fetch and display records from MySQL.
Update ➝ Modify existing records.
Delete ➝ Remove records safely.

**Tech Stack**: 
Programming Language: Java
Database: MySQL
JDBC Driver: For connecting Java with MySQL
**Setup & Installation**:

**Clone this repository:**
git clone https://github.com/your-username/your-repo-name.git

Open the project in your IDE (Eclipse / IntelliJ / VS Code).

Import the MySQL JDBC driver (Connector/J) into your project.
Create a database in MySQL:

**CREATE DATABASE crud_app;

Create a table (example for u**sers):

**CREATE TABLE users (

    id INT AUTO_INCREMENT PRIMARY KEY,
    
    name VARCHAR(100) NOT NULL,
    
    email VARCHAR(100) UNIQUE NOT NULL,
    
    password VARCHAR(100) NOT NULL
    
);
**

**Update database credentials in your Java code:**
Run the application.
