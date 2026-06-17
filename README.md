# Advanced Java Full-Stack Architecture

An enterprise-grade repository showcasing scalable backend microservices, secure RESTful APIs, and cloud-native application layouts. This portfolio serves as direct proof of production-ready development practices.

---

## 🛠️ Production Tech Stack
* **Language & Runtime:** Java 17 / OpenJDK
* **Core Frameworks:** Spring Boot 3.x, Spring Web, Spring Security
* **Data Access:** Spring Data JPA, Hibernate ORM
* **Database Management:** MySQL (Normalized to 3NF)
* **Containerization:** Docker / Multi-stage builds
* **API Documentation:** Swagger UI / Springdoc-openapi

---

## 📁 Repository Blueprint & Architecture

The codebase follows a strict **Layered Architecture Design Pattern** (Controller -> Service -> Repository -> Database) to ensure clean separation of concerns and decoupled components.

```text
advanced-java-fullstack/
│
├── 01-spring-boot-microservices/   # Enterprise REST APIs & System Security
│   ├── src/main/java/com/portfolio/
│   │   ├── controllers/            # REST Endpoints (@RestController)
│   │   ├── services/               # Business Logic Contracts & Implementations
│   │   ├── repositories/           # Database Access Layer (JpaRepository)
│   │   ├── models/                 # Persistent Entities (@Entity)
│   │   └── config/                 # Security & Beans Configuration
│   └── Dockerfile                  # Container build instructions
│
├── 02-fullstack-integrations/      # API Contracts & Frontend Handshakes
└── 03-cloud-native/                # Docker Compose & Enterprise Infrastructure
