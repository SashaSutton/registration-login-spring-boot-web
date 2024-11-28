# User Registration and Login with Spring Boot and Spring Security

## Overview
This project is a **User Registration and Login System** built with Spring Boot, Spring Security, and Thymeleaf. It provides functionality for users to register, log in, and access restricted content based on authentication.

---

## Features
- User registration with password encryption.
- Secure login with Spring Security.
- Role-based access control (default role: `ROLE_USER`).
- Front-end templates using Thymeleaf.
- Persistent data storage with JPA and H2/your chosen database.
- CSRF protection enabled for enhanced security.

---

## Technologies Used
- **Java**: Core programming language.
- **Spring Boot**: Framework for building the application.
- **Spring Security**: Manages authentication and authorization.
- **JPA/Hibernate**: ORM for database interactions.
- **Thymeleaf**: Server-side template engine for rendering views.
- **BCrypt**: Password hashing for secure storage.
- **H2**: (Optional) In-memory database for testing/development.
- **Maven**: Build automation tool.

---

## Getting Started

### Prerequisites
Ensure the following are installed on your machine:
- **Java 8+**
- **Maven**
- **H2 Database** (or configure another relational database like MySQL or PostgreSQL).

### Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
