## ⚠️ Note on Project Status

⚠️Incomplete Files Due to Technical Issues.
The existing codebase reflects the planned structure and initial setup.


# 📂TaskMaster
TaskMaster is a backend system built with Spring Boot to manage tasks, projects, and team collaborations. It includes user authentication, task assignment, filtering, and commenting.

## ✨ Features

- ✅ User registration and login with JWT authentication
- ✅ Role-based access control (`USER`, `ADMIN`)
- ✅ CRUD operations for tasks
- ✅ Team creation and management
- ✅ Assign tasks to users and teams
- ✅ Real-time task status updates (optional via WebSocket)
- ✅ Search, filter, and sort tasks
- ✅ MySQL database with JPA & Hibernate

---

## 🚀 Technologies Used

- Java 17
- Spring Boot 3
- Spring Security + JWT
- Spring Data JPA
- MySQL
- Maven
  
---

## 📦 Project Structure

taskmaster/
├── controller/ # REST API endpoints
├── dto/ # Data Transfer Objects
├── entity/ # JPA Entities
├── repository/ # Spring Data Repositories
├── service/ # Business Logic
├── security/ # JWT Filter, Configs
├── exception/ # Custom Exceptions
├── enums/ # Status, Role enums
├── TaskmasterApplication.java
└── resources/
├── application.properties




