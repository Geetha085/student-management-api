# Student Management REST API

A backend REST API built using **Python** and **Django REST Framework** to manage student records.  
This project demonstrates practical implementation of **RESTful APIs**, **HTTP methods**, **JSON request/response handling**, and **client–server architecture**.

This project is designed as a beginner-to-intermediate backend project and is suitable for showcasing on GitHub and resumes.

---

## Project Objective

The objective of this project is to build a backend service that allows clients to perform CRUD (Create, Read, Update, Delete) operations on student data using REST principles.

The API follows a clean and standard RESTful design and communicates using JSON format.

---

## Features

- Create a new student record
- Retrieve all student records
- Retrieve a student by ID
- Update student details using PUT (full update)
- Update student details using PATCH (partial update)
- Delete a student record
- JSON-based request and response handling
- RESTful endpoint design

---

## Technology Stack

- **Programming Language:** Python  
- **Framework:** Django  
- **API Framework:** Django REST Framework  
- **Database:** SQLite  
- **API Testing Tool:** Postman  

---

## Concepts Covered

- HTTP Protocol
- HTTP Methods (GET, POST, PUT, PATCH, DELETE)
- REST API principles
- JSON request and response handling
- Client–Server architecture
- CRUD operations
- Django ORM
- API testing using Postman

---

## REST API Endpoints

| HTTP Method | Endpoint | Description |
|------------|----------|-------------|
| POST | `/students/` | Create a new student |
| GET | `/students/` | Retrieve all students |
| GET | `/students/{id}/` | Retrieve a student by ID |
| PUT | `/students/{id}/` | Update student details (full update) |
| PATCH | `/students/{id}/` | Update student details (partial update) |
| DELETE | `/students/{id}/` | Delete a student |

---

## Sample JSON Request

```json
{
  "name": "Ravi",
  "email": "ravi@gmail.com",
  "course": "BBA",
  "age": 23
}
```
## Sample JSON Response

```json
{
  "id": 1,
  "name": "Ravi",
  "email": "ravi@gmail.com",
  "course": "BBA",
  "age": 23
}
```
---

## Request–Response Flow
- Client → HTTP Request → Django REST API → Database
- Client ← JSON Response ← Django REST API ← Database

---

## Live API
https://student-management-api-p1oa.onrender.com/students/

