# Library Management System

**Tech Stack:** Core Java • Spring Boot • H2 (in-memory) • Maven

## Project Overview
The Library Management System is a backend application designed to manage books and student records.  
Built with Spring Boot and an H2 in-memory database, this project demonstrates CRUD operations, REST APIs, and clean backend architecture.

## Run Locally
1. Install JDK 17+ and Maven.  
2. Build and run:
   ```bash
   mvn clean package
   mvn spring-boot:run
   ```

3. Access API and endpoints:
   ```text
   Base URL: http://localhost:8080/api/

   Books
   GET    /api/books        — list all books
   POST   /api/books        — add new book
   GET    /api/books/{id}   — get book by ID
   PUT    /api/books/{id}   — update book
   DELETE /api/books/{id}   — delete book

   Students
   GET    /api/students     — list all students
   POST   /api/students     — add new student
   GET    /api/students/{id} — get student by ID
   PUT    /api/students/{id} — update student
   DELETE /api/students/{id} — delete student

   Notes
   Uses H2 in-memory database for simplicity.
   For production, update application.properties.

   Package name: com.example.lms

   Author: Enugula Manasa
   ```
