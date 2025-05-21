# Quiz Application - Microservices Backend

## 🚀 Tech Stack
- Java 17+
- Spring Boot
- Spring Cloud (Eureka, API Gateway)
- Spring Data JPA
- PostgreSQL
- Maven
- Docker (optional)

## 🧩 Microservices Architecture
- **quiz-service** – Handles quiz creation and management
- **question-service** – Manages questions for quizzes
- **service-registry** – Eureka server for service discovery
- **api-gateway** – Centralized entry point for all services

## 🛠️ How to Run
1. Clone the repository
2. Start `service-registry`
3. Start `question-service` and `quiz-service`
4. Start `api-gateway`
5. Access services via `http://localhost:{port}`
