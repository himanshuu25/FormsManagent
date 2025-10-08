# Student Management System

## Project Overview
The **Student Management System (SMS)** is a **web-based Java application** that allows users to **manage student records** efficiently. Users can **insert, edit, delete, and view** student details. The project demonstrates **CRUD operations** using **Java Servlets**, **JDBC**, and follows **DTO (Data Transfer Object)** and **DAO (Data Access Object)** design patterns for a clean and maintainable structure.  

This system is ideal for beginners who want to understand the architecture of servlet-based applications and database interactions.

---

## Features
- **Insert Student**: Add new student details to the database.  
- **Edit Student**: Update existing student information.  
- **Delete Student**: Remove student records.  
- **View Student Details**: Display all student information.  
- **Structured Design**: Implements **DTO** and **DAO** patterns for better separation of concerns.  
- **Single Main Page**: `common.html` serves as the main navigation page with four buttons.  

---

## Technologies Used
- **Java** (Servlets & JDBC)  
- **HTML / CSS** (Frontend pages)  
- **Oracle Database / MySQL**  
- **Apache Tomcat** (Servlet container)  
- **Properties File** for database configuration (`database.properties`)  
- **web.xml** for servlet mapping  

---

---

## Database Setup
1. **Create Table**
```sql
CREATE TABLE StudentInfo (
    fname VARCHAR2(50),
    lname VARCHAR2(50),
    rollno VARCHAR2(10) PRIMARY KEY,
    branch VARCHAR2(50),
    course VARCHAR2(50),
    mobile VARCHAR2(15)
);
````
Design Patterns Used

- DTO (Data Transfer Object): Encapsulates student data for transferring between frontend and backend.

- DAO (Data Access Object): Handles all database operations separately from servlet logic.
