# 📝 Spring Boot To-Do Application

A minimal and elegant **To-Do List Web Application** built with **Spring Boot** and styled using **Bootstrap 5**.  
This app allows users to **add**, **toggle**, and **delete** tasks from a beautiful, clean UI — all backed by a PostgreSQL database.

![image](https://github.com/user-attachments/assets/97bebde9-315a-4268-91c0-25e8e90b3618)

---

## ✨ Features

- ✅ Add new tasks with ease
- 🔁 Mark tasks as completed or not completed
- ❌ Delete tasks instantly
- 🎨 Clean & professional UI powered by Bootstrap 5
- 🛢️ PostgreSQL database integration
- ⚙️ Built using Spring Boot (Java)

---

## 🛠️ Tech Stack

- **Backend**: Spring Boot, Spring MVC, Spring Data JPA
- **Frontend**: HTML + Thymeleaf + Bootstrap 5
- **Database**: PostgreSQL
- **Build Tool**: Maven

---

## 🚀 Getting Started

### 1. Clone the repository


2. Set up PostgreSQL
Create a database (e.g., todo_app)

Create a user with login permissions (e.g., testuser)

Grant all privileges on the database to the user

CREATE DATABASE todo_app;
CREATE USER testuser WITH PASSWORD 'yourpassword';
GRANT ALL PRIVILEGES ON DATABASE todo_app TO testuser;

3. Update application.properties
spring.datasource.url=jdbc:postgresql://localhost:5432/todo_app
spring.datasource.username=testuser
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

4. Run the application


🙌 Author
Vedant Bhamre
Spring Boot Developer | AI Enthusiast | Building Smart Tools for Education
📧 vedantbhamre17@gmail.com

⭐️ Show Some Love
If you liked the project, feel free to give it a ⭐️ on GitHub!
Pull requests and suggestions are welcome!


