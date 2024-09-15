# **Microservices Architecture with Spring Boot, Docker, Kubernetes**

This project demonstrates a microservices architecture for a simple bank built using Spring Boot and Spring Cloud. The services are containerized using Docker and deployed on Kubernetes, with additional tools for observability and security.

## **Table of Contents**
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Microservices](#microservices)
- [API Documentation](#api-documentation)
- [Monitoring & Observability](#monitoring--observability)
- [Security](#security)
- [Event-Driven Communication](#event-driven-communication)

---

## **Project Overview**

This project showcases a complete microservices architecture, focusing on building scalable, resilient, and secure systems. Each microservice is independently developed and deployed, following the principles of cloud-native applications. The architecture includes:

- **Service Discovery** with Eureka
- **API Gateway** with Spring Cloud Gateway
- **Centralized Configuration** with Spring Cloud Config
- **Monitoring & Observability** using Prometheus, Grafana, Loki, and Tempo
- **Security** with OAuth2 and OpenID Connect
- **Event-Driven Messaging** with RabbitMQ and Kafka

## **Technologies Used**

- **Java 11**
- **Spring Boot & Spring Cloud** (Eureka, Spring Cloud Gateway, Config Server, Resilience4J)
- **Docker** (Containerization)
- **Kubernetes** (Orchestration)
- **Google Kubernetes Engine (GKE)**
- **OAuth2 & OpenID Connect** (Security)
- **Prometheus, Grafana, Loki, Tempo** (Monitoring & Observability)
- **RabbitMQ & Kafka** (Messaging)
- **Postman** (API Testing)

## **Microservices**

The project consists of the following microservices:

1. **Accounts Service**: Microservicce for Accounts.
2. **Loans Service**: Microservicce for Loans.
3. **Cards Service**:  Microservicce for Cards.
4. **Config Server**: Centralized configuration management for microservices.
5. **Gateway Service**: Acts as an API Gateway for routing traffic to microservices.
6. **Discovery Service**: Eureka server for service discovery and registration.

## **API Documentation**

The APIs are documented using **Swagger** and the **OpenAPI Specification**.

## **Monitoring & Observability**

- Prometheus is used for monitoring metrics.
- Grafana provides visualizations and dashboards.
- Loki and Promtail are used for log aggregation.
- Tempo is used for distributed tracing.

## **Security**

The microservices are secured using OAuth2 and OpenID Connect. 

## **Event-Driven Communication**
- RabbitMQ is used for sending notifications.
- Kafka is implemented for asynchronous communication between services.




