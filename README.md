# 📚 Library Management System

**Tech Stack:** Core Java • Spring Boot • H2 (in-memory) • Maven • RESTful APIs  

---

## 📖 Project Overview
The **Library Management System** is a backend application built with **Spring Boot** to manage books and student records.  
It demonstrates clean backend design with **CRUD operations** and REST APIs, using an **H2 in-memory database** for easy local testing.  

This project highlights your skills in:
- Java & Spring Boot development
- Building RESTful APIs
- Working with in-memory databases
- Clean project architecture (MVC pattern)

---

## ✨ Features
- 📚 **Manage Books** → Add, update, delete, and view book records  
- 🧑‍🎓 **Manage Students** → Add, update, delete, and view student records  
- 🔗 RESTful API endpoints for easy integration  
- ⚡ Lightweight H2 database for quick setup and testing  

---

## 🛠️ Tech Highlights
- **Java + Spring Boot** → Backend logic & REST APIs  
- **H2 Database** → Lightweight in-memory DB  
- **Maven** → Build automation & dependency management  
- **CRUD Operations** → Core project functionality  

---

## 🚀 Run Locally
1. Install **JDK 17+** and **Maven** 
2. **Clone the repository:**
   ```bash
   git clone https://github.com/Enugula-Manasa/Library-Management-System.git
   ```
3. **Navigate to the project folder:**
   ```bash
   cd Library-Management-System
   ```
4. **Build and run the project:**
   ```bash
   mvn clean package
   mvn spring-boot:run
   ```
5. **Access the API:**
    👉 http://localhost:8080/api/
## 📌 Example Endpoints
- **📘 Books**
- `GET  /api/books`        → list all books
- `POST /api/books`      → add a new book
- `GET  /api/books/{id}`  → get book by ID
- `PUT  /api/books/{id}`   → update book
- `DELETE /api/books/{id}`   → delete book
- **🎓 Students**
- `GET  /api/students`        → list all students
- `POST /api/students`       → add a new student
- `GET  /api/students/{id}` → get student by id
- `PUT  /api/students/{id}`  → update student
- `DELETE /api/students/{id}` → delete student
## 📝 Notes
🗄️ Uses H2 in-memory database for simplicity.

🛠️ For production, update application.properties.

📦 Package name: com.example.lms
## 👩‍💻 Author
Enugula Manasa

