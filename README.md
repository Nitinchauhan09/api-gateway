# API Gateway for Quiz Application

The API Gateway acts as a single entry point for managing and routing requests to the **Quiz Service** and **Question Service**. It simplifies the interaction between clients and services by providing a centralized layer for request routing, load balancing.

---

## Features
- **Centralized Routing**: Directs requests to the appropriate services (Question Service and Quiz Service).
- **Simplified Client Communication**: Clients interact with a single endpoint instead of multiple services.
- **Service Registration and Discovery**: Integrates with the Eureka Server to dynamically discover services.
- **Load Balancing**: Distributes incoming requests across multiple instances of services.

---

## Tech Stack
- **Language**: Java
- **Framework**: Spring Boot
- **Dependencies**:
  - Spring Cloud Gateway
  - Eureka Client
- **Tools**: Postman (for API testing)

---

## Prerequisites
- Java 17 or later
- Eureka Server running
- Question Service and Quiz Service running and registered with Eureka Server

---

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nitinchauhan09/api-gateway.git
