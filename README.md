# Library Management System

*Tech Stack:* Core Java • Spring Boot • H2 (in-memory) • Maven

## Project Summary
A minimal backend application to manage books and students.  
Built with Spring Boot and H2 in-memory database to demonstrate CRUD operations and REST API development.

## Features
- Manage books: add, update, delete, and view
- Manage students: add, update, delete, and view
- RESTful APIs for easy integration
- Uses H2 in-memory database for local testing

## Run Locally
1. Install **JDK 17+** and **Maven**  
2. Clone the repository:
   ```bash
   git clone https://github.com/Enugula-Manasa/Library-Management-System.git
   cd Library-Management-System
3. Build and run:

bash
Copy code
mvn clean package
mvn spring-boot:run
4. Access API: http://localhost:8080/api/

Example Endpoints
Books

GET /api/books — list all books

POST /api/books — add new book

GET /api/books/{id} — get book by ID

PUT /api/books/{id} — update book

DELETE /api/books/{id} — delete book

Students

GET /api/students — list all students

POST /api/students — add new student

GET /api/students/{id} — get student by ID

PUT /api/students/{id} — update student

DELETE /api/students/{id} — delete student

Notes
Uses H2 in-memory database for simplicity.

For production, update application.properties.

Package name: com.example.lms

Author
Enugula Manasa
