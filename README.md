
# Full Stack CRUD Application

## Overview
This is a full stack CRUD (Create, Read, Update, Delete) application built with Java Spring Boot for the backend, React for the frontend, and MySQL for the database. 
The application performs basic CRUD operations on a sample entity(user).

## Features
- User-friendly interface built with React
- API built using Spring Boot for CRUD operations
- Data persistence using MySQL
- Fully responsive design

## Technologies Used
- **Backend**: Java Spring Boot
- **Frontend**: React.js
- **Database**: MySQL
- **Other**: Axios, REST API

## Prerequisites
- Java 11+
- Node.js
- MySQL

## Setup Instructions

### Backend Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/firdoushassan/fullstack-crudapp]
   cd fullstack-crudapp\src\main\java\com\crudapp\fullstack_crudapp
   ```
2. Configure MySQL:
   - Create a database named `crud_db`.
   - Update the `application.properties` file with your MySQL credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/crud_db
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```
3. Build and run the backend:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Run the frontend:
   ```bash
   npm start
   ```

## Usage
- Open your browser and go to `http://localhost:3000`.
- Interact with the application to create, view, update, and delete records.
