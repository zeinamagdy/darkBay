# NestJS REST API with JWT Authentication

A robust, production-ready backend application built with **NestJS**, featuring secure JWT-based authentication, an **SQLite database with ORM**, and interactive **Swagger API documentation**. Developed as a project component during the **neue fische** Web Development / Software Engineering Bootcamp.

---

## 🎓 Bootcamp Context & Team Methodology

This project was built during the **neue fische** bootcamp to apply enterprise-level backend development concepts in a collaborative setting. 

We used **Driver/Navigator Pair Programming**, rotating roles continuously:
* **Driver:** Focused on writing implementation code, module structure, and syntax.
* **Navigator:** Focused on reviewing logic in real-time, catching edge cases, verifying NestJS & ORM concepts, and checking documentation.

### Team Members
* https://github.com/savithacs
* https://github.com/GPlastok
* https://github.com/zeinamagdy

### Pair Programming Takeaways
* **Deep Architectural Alignment:** Building the NestJS module structure together ensured a shared understanding of dependency injection, controllers, services, and DTO validations.
* **Secure Auth Implementation:** Designing the JWT authentication workflow (guards, strategies, and token issuance) as a pair eliminated single-point-of-failure security oversights.
* **ORM & Database Management:** Pair programming allowed us to design clean database entities, relations, and migrations together without schema mismatches.

---

## 🛠️ Tech Stack & Architecture

* **Bootcamp Focus:** Full-Stack / Backend Engineering @ neue fische
* **Core Framework:** [NestJS](https://nestjs.com/) (Node.js / TypeScript)
* **Database & ORM:** SQLite with *(TypeORM / Prisma - edit as needed)*
* **Authentication:** Passport.js with JSON Web Tokens (JWT) & bcrypt hashing
* **API Architecture & Docs:** RESTful endpoints with OpenAPI / Swagger integration (`@nestjs/swagger`) and input validation (`class-validator`)

---

## 🚀 Key Features

* **JWT Authentication & Authorization:** Secure user sign-up, login, and route protection using custom NestJS Guards and Passport strategies.
* **Lightweight SQLite Persistence:** Zero-config relational database persistence managed seamlessly via an ORM layer.
* **Interactive OpenAPI/Swagger Docs:** Fully interactive API browser for endpoint testing and JWT authentication testing.
* **Modular Architecture:** Structured into feature modules (`AuthModule`, `UsersModule`) following NestJS best practices.

---

## 📖 API Documentation (Swagger)

This project includes interactive OpenAPI documentation generated directly from NestJS decorators.

When running the application, access the live Swagger UI at:
`http://localhost:3000/api` 

* **Features:** Live endpoint execution, request/response schema validation, and token authentication testing using the **Authorize** button.

---

## 📦 Getting Started

### Prerequisites
* Node.js (v18+ recommended)
* npm, yarn, or pnpm

### Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/zeinamagdy/darkBay
   cd repository-name
