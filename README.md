# Spring Boot REST API Example

This is a simple Spring Boot application that demonstrates how to build a RESTful web service using Java and Spring Boot. It includes basic CRUD operations, error handling, and configuration examples.

## 🚀 Features

- RESTful endpoints (`GET`, `POST`, `PUT`, `DELETE`)
- Spring Boot auto-configuration
- In-memory H2 database
- JPA/Hibernate integration
- Exception handling with `@ControllerAdvice`
- Unit and integration tests with JUnit
- Docker support (optional)

## 🛠️ Technologies

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Maven or Gradle
- JUnit 5

## 📦 Getting Started

### Prerequisites

- Java 17+
- Maven or Gradle
- IDE (IntelliJ IDEA recommended)

### Build and Run

```bash
# Clone the repo
git clone https://github.com/your-username/spring-boot-rest-api.git
cd spring-boot-rest-api

# Build the project
./mvnw clean package

# Run the app
java -jar target/spring-boot-rest-api-0.0.1-SNAPSHOT.jar
