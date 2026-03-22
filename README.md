# Marksheet Generator System

A Spring Boot and MongoDB based web application for managing student marksheets with secure role-based authentication for teachers and students.

---

## Project Overview

This system is designed to manage student marksheets efficiently. It provides features for teachers to add and manage marksheets, and for students to securely view their results.

---

## Features

* Add and manage student marksheets
* Automatic calculation of total marks, percentage, and grade
* Role-based authentication (Teacher and Student)
* Secure login system using Spring Security
* Search marksheets by student name or roll number
* Dashboard with basic analytics
* Separate interfaces for teachers and students

---

## Technology Stack

* Java 17
* Spring Boot
* Spring Security
* MongoDB
* Thymeleaf
* HTML, CSS
* Maven

---

## Project Structure

Controllers:

* HomeController.java
* TeacherController.java
* StudentController.java
* MarksheetController.java
* MarksheetApiController.java

Services:

* MarksheetService.java
* StudentUserDetailsService.java

Models:

* Marksheet.java
* StudentUser.java

Repositories:

* MarksheetRepository.java
* StudentUserRepository.java

Configuration:

* SecurityConfig.java
* MongoConfig.java

Frontend Templates:

* index.html
* login.html
* teacher_login.html
* student_login.html
* dashboard.html
* teacher_dashboard.html
* marksheet_form.html
* marksheet_list.html
* marksheet_view.html
* error.html

---

## Setup Instructions

### Step 1: Clone the repository

```bash id="step1"
git clone https://github.com/divmehta093-sudo/Marksheet_Generator
```

### Step 2: Configure MongoDB

```properties id="step2"
spring.data.mongodb.uri=mongodb://localhost:27017/marksheetdb
```

### Step 3: Run the application

```bash id="step3"
mvn spring-boot:run
```

### Step 4: Open in browser

```
http://localhost:8080
```

---

## Default Login

Teacher:

* Username: teacher1
* Password: teacher1

---

## Author

Divya Mehta
GitHub: https://github.com/divmehta093-sudo

---

## License

This project is licensed under the MIT License.
