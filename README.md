# API REST - Proof of Concept

This project is a proof of concept implementing a simple REST API using **Spring Boot**. It demonstrates how to expose a basic REST endpoint.

## Description

The API exposes a single endpoint `GET /sayHello` that responds with a simple greeting message.

### Technologies Used

- **Java**: Main programming language.
- **Spring Boot**: Framework used to build the REST API.
- **Maven**: Tool for dependency management and project building.

## Project Structure

```plaintext
src/main/java
└── com
    └── mipagina
        └── api_rest
            └── controller
                └── HelloWorldController.java
            └── ApiRestApplication.java
```
## How to Run the Project:
Prerequisites:
- Java 17 or later.
- Maven installed.

Steps to Run:
1. Clone this repository::
```bash
git clone https:https://github.com/alfadexters/ApiRest-with-Java.git
cd ApiRest-with-Java
```

2. Compile and run the project with Maven:
```bash
mvn spring-boot:run
```
3. Access the endpoint from your browser or a testing tool like Postman:
```bash
   http://localhost:8080/sayHello
```
4. You will receive the following response:
```bash
   Hello World, I am Richard
```
