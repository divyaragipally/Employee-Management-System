# Employee Management System

A full-stack Employee Management System built using **React.js, Spring Boot, Spring Data JPA, and MySQL**.  
This application provides CRUD operations to manage employee details, including adding, viewing, updating, and deleting employee records.

##  Features

- Add new employees
- View all employees
- Update employee information
- Delete employee records
- Manage department details
- REST API integration between frontend and backend
- Responsive user interface

---

##  Technologies Used

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Axios
- React Router
- Vite

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- RESTful APIs
- Maven

### Database
- MySQL

### Development Tools
- Spring Tool Suite (STS)
- Visual Studio Code
- Postman
- Git & GitHub

---

##  Project Structure

```
Employee-Management-System
│
├── backend
│   ├── src/main/java
│   │   └── com.ihub.www
│   │       ├── controller
│   │       ├── entity
│   │       ├── service
│   │       ├── repo
│   │       └── exception
│   │
│   ├── src/main/resources
│   │   └── application.properties
│   │
│   └── pom.xml
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── services
│   │   └── App.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# Installation and Setup

## Backend Setup (Spring Boot)

### 1. Clone the repository

```bash
git clone https://github.com/divyaragipally/Employee-Management-System.git
```

### 2. Open Backend Project

Open the `backend` folder in **Spring Tool Suite (STS)**.

### 3. Configure MySQL Database

Update the database configuration in:

```
backend/src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_management_system
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
```

### 4. Run Spring Boot Application

The backend runs on:

```
http://localhost:9191
```

---

# Frontend Setup (React)

### 1. Navigate to frontend folder

```bash
cd frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start React application

```bash
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

# API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/v1/employee` | Get all employees |
| GET | `/api/v1/employee/{id}` | Get employee by ID |
| POST | `/api/v1/employee` | Add a new employee |
| PUT | `/api/v1/employee/{id}` | Update employee details |
| DELETE | `/api/v1/employee/{id}` | Delete employee |

---

#  Application Screenshots


```
screenshots/
├──Login.png
├── add-employee.png
└── update-employee.png
```

---

# Learning Outcomes

- Developed a complete full-stack application
- Implemented REST APIs using Spring Boot
- Connected Spring Boot with MySQL using JPA/Hibernate
- Integrated React frontend with backend APIs using Axios
- Implemented CRUD operations
- Learned Git and GitHub project management

---

# Author

**Divya Ragipally**

GitHub:  
https://github.com/divyaragipally
