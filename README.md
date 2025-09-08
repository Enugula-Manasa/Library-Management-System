# Library Management System

**Tech stack:** Core Java • Spring Boot • H2 (in-memory) • Maven

## Project summary
Minimal Library Management System backend to demonstrate CRUD operations for books and students,
using Spring Boot and an in-memory H2 database for easy local testing.

## Run locally
1. Install JDK 17+ and Maven.
2. Build and run:
```bash
mvn clean package
mvn spring-boot:run
```
3. The API base: `http://localhost:8080/api/`

## Endpoints (examples)
- `GET  /api/books` — list books
- `POST /api/books` — add book (JSON)
- `GET  /api/books/<built-in function id>` — get book by id
- `PUT  /api/books/<built-in function id>` — update book
- `DELETE /api/books/<built-in function id>` — delete book

## Notes
- This project uses H2 in-memory database for simplicity. For production, change datasource in application.properties.
- Replace package `com.example.lms` if desired.

## Author
Enugula Manasa
