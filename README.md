# SmartShop Microservices

SmartShop is a backend-only e-commerce system built with Spring Boot and microservices architecture. It handles essential operations like product management, ordering, inventory, and notifications, with a focus on scalability, observability, and secure authentication.

---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot (Microservices)**
- **Spring Data JPA / Hibernate**
- **MySQL**
- **Kafka (Event-driven communication)**
- **Eureka (Service Discovery)**
- **API Gateway**
- **Keycloak (OAuth2 + JWT Security)**
- **Docker & Docker Compose**
- **Zipkin, Prometheus, Grafana (Monitoring & Tracing)**

---

## 📦 Microservices Included

| Service              | Description                                 |
|----------------------|---------------------------------------------|
| **Product Service**   | Create and fetch products                   |
| **Order Service**     | Place orders, trigger events                |
| **Inventory Service** | Tracks product stock                        |
| **Notification Service** | Sends notifications for new orders      |
| **API Gateway**       | Central entrypoint to access all services  |
| **Discovery Server**  | Eureka for service registration/discovery  |

---

## 🔐 Security

- Integrated with **Keycloak** for authentication & authorization.
- All microservices are protected via **OAuth2** and use **JWT tokens**.

---

## 📊 Monitoring & Observability

- **Zipkin** for distributed tracing.
- **Prometheus** + **Grafana** dashboards for service health metrics.

---

## 🐳 Docker Support

All services are containerized. One command via `docker-compose.yml` spins up the entire architecture locally.

```bash
docker-compose up --build
📎 API Testing
Postman collections are available to test:

Product creation and retrieval

Order placement with stock checks

Notifications triggered via Kafka

🚀 Features Covered
✅ Backend-only architecture (no frontend)

✅ RESTful APIs

✅ Async communication using Kafka

✅ MySQL data persistence

✅ Clean domain-driven design

✅ Production-ready observability stack

✅ Secure access via Keycloak

📁 Folder Structure
pgsql
Copy
Edit
├── product-service
├── order-service
├── inventory-service
├── notification-service
├── discovery-server
├── api-gateway
├── realms/ (Keycloak config)
├── prometheus/ (Monitoring)
├── docker-compose.yml
🧠 What I Learned
Building end-to-end REST APIs in a distributed architecture

Managing service registration, routing, and security in real-world style projects

Working with Docker and deploying multi-container setups

Debugging issues across distributed logs, traces, and metrics

👨‍💻 Author
Balaji Matta
Backend Developer | Spring Boot Enthusiast
GitHub Profile

📌 Note
This is a backend-only system intended for technical evaluation. A future version may include a frontend UI layer or admin dashboard.
