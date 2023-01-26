# Spring Boot 3.0 Security with JWT Implementation
This project demonstrates the implementation of security using Spring Boot 3.0 and JSON Web Tokens (JWT). It includes the following features:

## Features
* User registration and login with JWT authentication
* Password encryption using BCrypt
* Role-based authorization with Spring Security
* Customized access denied handling

## Technologies
* Spring Boot 3.0
* Spring Security
* JSON Web Tokens (JWT)
* BCrypt
* Maven
 
## Getting Started
To get started with this project, you will need to have the following installed on your local machine:

* JDK 8+
* Maven 3+
* Local Postgres Database Server
* Postman Client (for endpoint testing)


To build and run the project, follow these steps:

* Clone the repository: `git clone https://github.com/hafizulhaque/spring-boot-jwt.git`
* Create a database named: `jwt-db` with user: `postgres` & password: `pass`
* Navigate to the project directory: cd spring-boot-jwt
* Build the project: mvn clean install
* Run the project: mvn spring-boot:run 

-> The application will be available at http://localhost:8080.