# Java Standalone CRUD Application with MySQL

This is a Java application that demonstrates CRUD (Create, Read, Update, Delete) operations using MySQL database.

## Prerequisites

Before running this application, make sure you have:
1. Java Development Kit (JDK) installed
2. MySQL Server installed and running
3. MySQL JDBC Connector (mysql-connector-java) installed

## Setup Instructions

1. **Install MySQL:**
   - Download and install MySQL Server from the official website
   - During installation, note down your MySQL root password
   - Start the MySQL service

2. **Create Database:**
   ```sql
   CREATE DATABASE crud_db;
   USE crud_db;
   CREATE TABLE students (
       id INT PRIMARY KEY AUTO_INCREMENT,
       name VARCHAR(100),
       age INT,
       email VARCHAR(100)
   );
   ```

3. **Install MySQL Connector:**
   - Download mysql-connector-java from Maven Central
   - Add the .jar file to your project's classpath

## Running the Application

1. Open Command Prompt (cmd) and navigate to the project directory:
   ```bash
   cd path/to/your/project/java-crud-app
   ```

2. Compile the Java program:
   ```bash
   javac src/Main.java
   ```

3. Run the program:
   ```bash
   java -cp src:mysql-connector-java-x.x.x.jar Main
   ```
   (Replace x.x.x with your MySQL connector version)

## Features

- Create new student records
- Read/view existing student records
- Update student information
- Delete student records

## Note

- Make sure MySQL server is running before executing the program
- Verify that your MySQL connection parameters (username, password, database name) match those in the code
- The application uses JDBC for database connectivity

## Troubleshooting

If you encounter any issues:
1. Check if MySQL service is running
2. Verify database connection parameters
3. Ensure MySQL connector is properly added to classpath
4. Check for any compilation errors in the Java code

## Contact

For any questions or issues, please contact your instructor or lab assistant.
