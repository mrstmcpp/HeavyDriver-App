**# HeavyDriver-App
This project is a scalable ride hailing service built with a microservices architecture. Each microservice has its own repository. This repository serves as a central documentation hub.
# HeavyDriver Ride Hailing System (Microservices Architecture)

This project is a scalable **ride hailing backend** built with a **microservices architecture**.  
Each microservice has its own repository. This repository serves as a central documentation hub.

---

## 🚀 Tech Stack
- **Backend:** Spring Boot (Java)
- **Frontend:** React, SockJS, Google Maps API
- **Database:** MySQL, Redis
- **Messaging:** Apache Kafka, RetroFit
- **Service Discovery:** Netflix Eureka
- **Authentication:** JWT (HttpOnly)
- **Others:** WebSockets (STOMP), Redis GeoHash, Flyway migrations

---

## 🏗️ Microservices Overview
- **Eureka Service Discover Server** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-EurekaDiscoveryService)
- **API Gateway** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-ApiGateway)
- **Client Socket Service** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-ClientSocketService)
- **Location Service** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-LocationService)
- **Auth Service** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-AuthService)
- **Booking Service** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-BookingService)
- **Fare Service** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-FareService)
- **Review Service** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-ReviewService)
- **Passenger Frontend** → [Repo Link](https://github.com/mrstmcpp/heavydriver-frontend)
- **Driver Frontend** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-Driver-Frontend)
- **Entity Repo** → [Repo Link](https://github.com/mrstmcpp/HeavyDriver-EntityService)
  
---

## 📌 Features
- Engineered and implemented a **Microservices-based ride-booking platform** with modular components like **Authorization, Booking, Location, Client-Socket & Review services** for enhanced scalability.
- Ensured **clean architecture** with layered services and DTOs for maintainability.
- Integrated **Google Maps APIs** for ETA, route optimization, and fare calculation.
- Secured RESTful endpoints using **JWT-based authentication** with HttpOnly cookies for safe session management.
- Real-time driver location tracking using **Redis GeoHash** for efficient nearby-driver searches.
- Implemented **STOMP WebSocket** for live driver tracking and instant booking status updates.
- Integrated **Kafka & Retrofit** for async booking events and decoupled service communication.
- Employed **Flyway** for automated, version-controlled DB migrations in MySQL services.
- Applied **SOLID principles** and **Builder design pattern** for clean, maintainable, and testable code.
- Horizontal scalability with independent microservices.

---

## ⚡ Running Locally
Each microservice has its own setup instructions.  
For quick start:
1. Clone the repo you need (`git clone ...`)
2. **Start the Eureka Server first** so that all services can register and discover each other.
3. Run your **Kafka** & **Redis** containers at **9092** & **6379** ports respectively.
4. Run with Spring Boot (`./gradlew bootRun`)

---
<!-- ## 📂 Architecture Diagram
(Add your architecture diagram here as an image, e.g. `![Architecture](docs/architecture.png)`)

--- -->



---
**
