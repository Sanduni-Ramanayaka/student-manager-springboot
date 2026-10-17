# Student Registration System

A web application developed using Spring Boot, Thymeleaf, and an H2 database to manage student registrations.

## Features

- Register new students
- View registered students
- Edit student details
- Delete student records
- Validate student information
- Prevent duplicate email addresses

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Thymeleaf
- H2 Database
- Maven
- HTML and CSS

## How to Run

1. Clone or download the repository.
2. Open the project in VS Code or IntelliJ IDEA.
3. Ensure JDK 21 (or the version configured in `pom.xml`) is installed.
4. Allow Maven to download the dependencies.
5. Run `StudentManagerApplication.java`.
6. Open http://localhost:8080 in your browser.

## H2 Database Console

Open http://localhost:8080/h2-console while the application is running.

- **JDBC URL:** `jdbc:h2:mem:studentdb`
- **Username:** `sa`
- **Password:** Leave empty

Note: This project uses an in-memory H2 database. Data is lost when the application stops.
