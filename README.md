# User Management API – Spring Boot

A production-style RESTful API for user management built using Spring Boot, demonstrating secure backend design, authentication, and scalable architecture.

---

## 🚀 Features
- CRUD operations for users (Create, Read, Update, Delete)
- JWT-based authentication and role-based access control
- Input validation for all endpoints
- Global exception handling with structured responses
- Pagination and sorting support
- Unit testing using JUnit and Mockito
- Dockerized setup using Docker and Docker Compose

---

## 🛠 Tech Stack
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA (Hibernate)
- PostgreSQL
- Maven
- Docker

---

## 🔐 Security
- JWT authentication implemented for securing APIs
- Role-based access control (RBAC)
- Public endpoints for authentication (login/register)

---

## 📦 API Endpoints

| Method | Endpoint        | Description              |
|--------|----------------|--------------------------|
| GET    | /users         | Get all users            |
| GET    | /users/{id}    | Get user by ID           |
| POST   | /users         | Create new user          |
| PUT    | /users/{id}    | Update user              |
| DELETE | /users/{id}    | Delete user              |

---

## 🧪 Testing
- Unit tests implemented for service and controller layers
- Tools: JUnit, Mockito

---

## 🐳 Deployment
- Dockerized using Docker and Docker Compose
- Easily deployable in containerized environments

---

## 📖 Notes
- Designed following clean architecture principles
- Can be extended into a microservices-based system
