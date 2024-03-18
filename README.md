
## UserService - Spring Boot Application

Welcome to the UserService Spring Boot application! This application provides a user management system where you can perform various CRUD (Create, Read, Update, Delete) operations on users.


## Getting Started

To get started with the UserService Spring Boot application, follow the instructions below.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Java 8 or higher.
- Apache Maven.
-  MongoDB.

## Installation

1. Clone this repository to your local machine:

    ```
    git clone <repository-url>
    ```

2. Navigate into the project directory:

    ```
    cd userservice-spring-boot
    ```

3. Build the project using Maven:

    ```
    mvn clean install
    ```

## Usage

To run the UserService Spring Boot application, follow these steps:

1. Ensure your MongoDB database is running and accessible.
2. Update the `application.properties` file with your database configuration.
3. Run the Spring Boot application:

    ```
    mvn spring-boot:run
    ```

The application will start and be accessible at `http://localhost:8080`.

## Endpoints

The following endpoints are available in this application:

- `GET /users`: Get all users.
- `GET /users/{id}`: Get user by ID.
- `GET /users/{byName}: Get user by their name
- `POST /users`: Create a new user.
- `PUT /users/{id}`: Update an existing user.
- `DELETE /users/{id}`: Delete a user by ID.

## Configuration

You can configure the application by modifying the `application.properties` file. Here, you can change the database settings, server port, logging configuration, etc.

