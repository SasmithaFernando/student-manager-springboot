# Student Registration System

A web application developed using Spring Boot, Thymeleaf, and the H2 database to manage student records.

## Features

- Register new students
- View registered students
- Edit student details
- Delete student records
- Validate student information
- Store data using the H2 database

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Thymeleaf
- H2 Database
- HTML and CSS
- Maven

## How to Run

1. Install JDK 17 or later.
2. Clone or download this repository.
3. Open the project in VS Code or IntelliJ IDEA.
4. Run the `StudentManagerApplication.java` file.
5. Open http://localhost:8080 in your browser.

## H2 Database Console

Open http://localhost:8080/h2-console while the application is running.

- JDBC URL: `jdbc:h2:mem:studentdb`
- Username: `sa`
- Password: Leave empty

**Note:** The database uses in-memory storage, so the data is cleared when the application stops.