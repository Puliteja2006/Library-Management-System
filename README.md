 # Library Management System

A Java-based console application that manages library books using JDBC and MySQL.
This project demonstrates backend development concepts such as database connectivity, CRUD operations, and modular Java application architecture.


## Project Overview:

The Library Management System allows users to manage books in a library through a command-line interface.
The system interacts with a MySQL database using JDBC, enabling persistent storage and management of book records.

This project showcases practical backend development skills including:

- Java Object-Oriented Programming
- Database integration with JDBC
- CRUD operations implementation
- Structured application design


## Features:

✔ Add new books to the library
✔ View all available books
✔ Issue books to users
✔ Return issued books
✔ Delete books from the library
✔ Menu-driven console interface
✔ Persistent storage using MySQL database


## Tech Stack:

Technology| Purpose
Java| Core programming language
JDBC| Database connectivity
MySQL| Data storage
NetBeans IDE| Development environment


## Project Structure:

Library-Management-System
│
├── src
│   └── librarymanagement
│        ├── Book.java
│        ├── BookManager.java
│        ├── DatabaseConnection.java
│        └── LibraryApp.java
│
├── nbproject
├── build.xml
├── manifest.mf
└── README.md


## Database Schema:

CREATE DATABASE library_db;

USE library_db;

CREATE TABLE books (
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(100),
    author VARCHAR(100),
    status VARCHAR(20)
);

The status field tracks whether the book is:

Available
Issued


## How to Run the Project:

1. Clone the repository
2. Import the project into NetBeans or IntelliJ IDEA
3. Create the MySQL database using the provided SQL script
4. Update database credentials in "DatabaseConnection.java"
5. Run "LibraryApp.java"


## Example Console Output:

----- Library Management System -----

1 Add Book
2 View Books
3 Issue Book
4 Return Book
5 Delete Book
6 Exit


## Future Improvements:

- Implement Search Book feature
- Add GUI version using Java Swing / JavaFX
- Convert application into a Spring Boot REST API
- Add user authentication and role-based access
- Build a web-based library system


## Author:

Puli Sai Srinivasa Teja

Aspiring Software Development Engineer (SDE) passionate about building backend systems using:

- Java
- JDBC
- MySQL
- Spring Boot


⭐ If you find this project useful, feel free to star the repository.
