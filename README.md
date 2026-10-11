# Student Activity Tracking System

## 📌 Project Overview

The Student Activity Tracking System is a full-stack web application developed to manage student information and track student activities in one place. It provides a user-friendly interface and a backend system to handle student data efficiently.

The application uses React for the frontend, Spring Boot for backend development, and MySQL for database management.

## 🚀 Features

- Student information management
- Add, view, update, and delete student records (CRUD operations)
- REST API integration between frontend and backend
- Database connectivity using MySQL
- Responsive and user-friendly interface
- Organized backend structure for maintainability

## 🛠️ Technologies Used

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3

**Backend**
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- REST APIs

**Database**
- MySQL

**Tools**
- Git and GitHub
- Maven
- Postman
- VS Code / IntelliJ IDEA / Eclipse

## 🏗️ Application Architecture

The application follows a frontend-backend architecture:

- **Frontend:** React handles the user interface.
- **Backend:** Spring Boot processes requests and implements application logic.
- **Database:** MySQL stores student information.
- **Communication:** REST APIs connect the frontend with the backend.

## ⚙️ Installation and Setup

### Prerequisites

Install the following tools before running the application:

- Java JDK
- Node.js and npm
- MySQL Server
- Maven
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Vishallande123/student-tracking-system.git
cd student-tracking-system
```

### 2. Run the Frontend

```bash
npm install
npm run dev
```

Open the local URL displayed in your terminal.

### 3. Run the Backend

Open the Spring Boot backend project in your IDE.

Configure the MySQL database connection in `application.properties`, then run the Spring Boot application.

Example configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_tracking
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Create the database in MySQL if it does not already exist. Replace the username and password with your local database credentials.

**Note:** The backend may be maintained in a separate repository. If so, clone and configure that repository separately.

## 🎯 Project Objective

The main objective of this project is to simplify student information management through a web-based application and demonstrate full-stack development using React, Spring Boot, and MySQL.

## 👨‍💻 Author

**Vishal Lande**

- GitHub: [Vishallande123](https://github.com/Vishallande123)

## 📄 License

This project is intended for learning and educational purposes.
