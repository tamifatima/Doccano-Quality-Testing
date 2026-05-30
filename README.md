# Doccano-Quality-Testing
🚀 **Software Quality Engineering Semester Project – Doccano-Based Annotation Management System (Testing & Quality Engineering)**

This project focuses on applying **Software Quality Engineering (SQE)** principles to a web-based **annotation management system** built around the open-source **Doccano** platform. The goal was to design, implement, and document a structured testing strategy for a production-style system using modern DevOps and testing practices.

### 📌 Project Overview

The system was intended to support annotation and dataset management through a multi-container architecture using Docker. The project emphasizes:

* Functional and non-functional testing design
* Deployment and environment setup
* API, security, and performance testing planning
* Automation and CI/CD strategy design
* Real-world debugging and troubleshooting of deployment environments

Although the system could not be fully deployed due to frontend dependency and environment-related issues, extensive engineering effort was invested in deployment, debugging, and quality planning.

### 🛠️ Technologies & Tools Used

**Development Platform / Technologies**

* Docker & Docker Compose
* Django (Backend)
* PostgreSQL Database
* RabbitMQ Message Broker
* Celery Workers
* Nginx Reverse Proxy
* Vue.js / Node.js (Frontend – Planned)

**Software Quality Engineering Tools**

* Postman (API Testing)
* Selenium WebDriver *(Planned)*
* Apache JMeter *(Planned)*
* SonarQube *(Planned)*
* GitHub Actions *(Planned)*

### ✅ Project Scope

**In-Scope Modules**

* User Registration & Login
* Role-Based Access Control
* Annotation Project Management
* Dataset Uploads
* API Endpoint Testing
* Database Connectivity & Migrations

**Out-of-Scope Modules**

* Third-party integrations
* OAuth authentication
* Email notification services
* Cloud deployment (AWS/GCP)

### 🧪 Testing Strategy

The project includes a professional SQE testing framework covering:

* **Functional Testing** – Authentication, project creation, API flows
* **Negative Testing** – Invalid login and authorization checks
* **Security Testing** – RBAC, authentication, password hashing
* **Performance Testing (Planned)** – Concurrent user load with Apache JMeter
* **Automation Testing (Planned)** – Selenium-based UI testing
* **CI/CD Pipeline (Planned)** – GitHub Actions + quality gates

### ⚠️ Deployment Challenges Encountered

During deployment, several real-world DevOps challenges were addressed, including:

* Docker Compose configuration issues
* Port binding conflicts (Nginx)
* Docker network and upstream resolution failures
* Missing frontend build artifacts (`index.html`)
* Node.js/npm execution policy restrictions
* Git dependency installation errors

Despite deployment limitations, backend initialization, database migrations, and container orchestration were partially validated.

### 👩‍💻 Team Members

* Tahreem Fatima (BSEF23M535)
* Saima Ghulam Mustafa (BSEF23M536)
* Uswah Zulfiqar (BSEF23M548)

### 🎯 Project Objective

This project demonstrates the practical application of **Software Quality Engineering, testing strategy design, deployment troubleshooting, and DevOps-oriented debugging** in a real-world multi-service software environment.
