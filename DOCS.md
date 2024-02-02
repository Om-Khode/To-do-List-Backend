# Spring Boot App - Todo List Backend

This document provides instructions on setting up and running the Spring Boot app with Postgres database locally.

## Technologies Used

- Spring Boot
- Postgres
- Java

## Instructions

1. Clone the repository:

   ```
   git clone https://github.com/Om-Khode/To-do-List-Backend
   cd To-do-List-Backend
   ```

2. Configure PostgreSQL:

   - Create a PostgreSQL database named 'todolist'.
   - Update `application.properties` with your database configurations.

3. Build and run the Spring Boot app:

   ```
   ./mvnw spring-boot:run
   ```

4. Access the backend API at 'http://localhost:8080'.
