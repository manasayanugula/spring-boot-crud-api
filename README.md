# User Management API – Spring Boot (Production-Ready)

This is a **RESTful CRUD API for User Management** built using Spring Boot, designed to demonstrate production-ready backend architecture, security, testing, and deployment practices.

---

## 🚀 Project Overview
- Build a secure, scalable, and maintainable backend API.
- Demonstrates **Spring Boot microservices architecture**, **JWT authentication**, **role-based access**, **validation**, **unit testing**, and **Dockerized deployment**.
- Ideal for learning or showcasing **real-world backend engineering skills**.

---

## 🛠 Tech Stack
- **Backend:** Java 17, Spring Boot, Spring Data JPA, Spring Security  
- **Database:** PostgreSQL  
- **Testing:** JUnit, Mockito  
- **API Testing:** Postman (collection included)  
- **Build Tool:** Maven  
- **Containerization:** Docker & Docker Compose  
- **Documentation:** Swagger (optional but recommended)  

---

## ⚡ Features
- **CRUD Operations** for Users
  - Create, Read, Update, Delete
- **JWT Authentication** with Role-Based Access Control
- **Input Validation** for all endpoints
- **Global Exception Handling** for structured error responses
- **Pagination & Sorting** for listing users
- **Unit Testing** for service and controller layers
- **Dockerized Deployment** for easy setup
- **Swagger API Documentation** (optional)
- Ready for integration in microservices architecture

---

## 📦 API Endpoints

| Method | Endpoint       | Description                 |
|--------|----------------|-----------------------------|
| GET    | /users         | Get all users               |
| GET    | /users/{id}    | Get a user by ID            |
| POST   | /users         | Create a new user           |
| PUT    | /users/{id}    | Update an existing user     |
| DELETE | /users/{id}    | Delete a user by ID         |

> JWT authentication protects all endpoints except login/register.

---

## 🧪 Postman Collection
A Postman collection is included: `postman_collection.json`  
You can import it to test all endpoints.

---

## 🏗 Project Structure

