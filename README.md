# Hibernate CRUD Demo

A simple Java project demonstrating Hibernate ORM CRUD operations with MySQL database.

## Features

- **Create**: Add new student records
- **Read**: Query and retrieve student data
- **Update**: Modify existing student information
- **Delete**: Remove student records
- **Primary Key Demo**: Understanding Hibernate ID generation

## Tech Stack

- Java
- Hibernate 5.2.0
- MySQL 8.0
- Maven

## Setup

1. Configure database connection in `src/main/resources/hibernate.cfg.xml`
2. Run SQL scripts in `sql-scripts/` to create database schema
3. Execute Maven build: `mvn compile`

## Demo Classes

- `CreateStudentDemo` - Create new students
- `ReadStudentDemo` - Query students
- `UpdateStudentDemo` - Update student data
- `DeleteStudentDemo` - Delete students
- `QueryStudentDemo` - Advanced queries
- `PrimaryKeyDemo` - ID generation examples

## Entity

The `Student` entity includes:
- ID (auto-generated)
- First Name
- Last Name
- Email

Run any demo class as a Java application to see Hibernate in action.
