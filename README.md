# Warehouse Management System – Core Java & JDBC Project

## Project Objective
The objective of this project is to develop a **menu-driven Warehouse Management System** using **Core Java and JDBC**.  
This project focuses on strengthening **Java programming fundamentals**, understanding **real-world requirements**, and applying **Object-Oriented Programming (OOP)** concepts along with **exception handling** and **database connectivity**.

The system allows users to manage products stored in a warehouse efficiently through a console-based interface.

---

## Task Description
The Warehouse Management System is a **console-based application** that performs basic warehouse operations using a relational database.

### Functional Requirements:
- Add new products to the warehouse
- View all available products
- Delete products using Product ID
- Validate product existence before operations
- Handle invalid inputs and database errors gracefully
- Follow layered architecture for clean code structure

### Application Features:
- Menu-driven program using `Scanner`
- CRUD operations using JDBC
- Uses MySQL database for data persistence
- Follows proper package structure:
  - `model`
  - `dao`
  - `service`
  - `util`
  - `exception`
  - `main`

---

## Concepts and Technologies Used

### Core Java Concepts:
- Object-Oriented Programming (OOP)
  - Classes and Objects
  - Encapsulation
  - Abstraction (Interfaces)
- Exception Handling
  - Try-catch blocks
  - Custom exceptions
- Collections (where applicable)
- Input handling using `Scanner`

### JDBC Concepts:
- JDBC Driver
- `Connection`
- `PreparedStatement`
- `ResultSet`
- CRUD operations
- Database connectivity and resource management

### Database:
- MySQL
- SQL (DDL & DML)
- Table creation and data manipulation

### Design & Architecture:
- DAO (Data Access Object) Pattern
- Service Layer for business logic
- Separation of concerns
- Clean and modular code structure

---

## Project Structure (Overview)

com.wms
- model        → Product entity class
- dao          → DAO interfaces and implementations
- service      → Business logic and validations
- util         → Database connection utility
- exception    → Custom exceptions
- main         → Menu-driven application (entry point)


