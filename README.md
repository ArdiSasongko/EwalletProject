# 💸 WalletSync: Microservices E-Wallet Powerhouse

## 🌟 Project Overview

WalletSync is a cutting-edge, production-ready e-wallet backend that transforms financial interactions through intelligent microservices architecture. Built with Go's performance and reliability, this platform delivers a secure, scalable solution for modern digital transactions.

## 🚀 Architectural Highlights

### Microservices Ecosystem
- **Decoupled, Independent Services**: Each microservice owns its domain, ensuring:
  - Rapid development and deployment
  - Easier maintenance and scaling
  - Fault isolation and resilience

### Security-First Design
- **Multi-Layer Authentication**
  - JWT-based secure token management
  - Middleware-enforced endpoint protection
  - Granular access control across services

### Performance & Scalability
- **Go Fiber Framework**: Lightweight, blazing-fast routing
- **SQLC**: Compile-time type-safe SQL queries
- **Docker Containerization**: Seamless deployment and environment consistency

## 🔧 Microservices Architecture

### 1. User Service (`EwalletProjects-user`)
- 🔐 Authentication Powerhouse
  - Robust user registration
  - Secure login/logout mechanisms
  - Intelligent token refresh strategies

### 2. Wallet Service (`EwalletProjects-wallet`)
- 💰 Financial Operations Hub
  - Instant wallet creation
  - Real-time balance management
  - Comprehensive transaction tracking

### 3. Transaction Service (`EwalletProjects-transaction`)
- 💳 Transaction Management Engine
  - Flexible transaction creation
  - Advanced transaction updating
  - Comprehensive refund capabilities

### 4. Notification Service (`EwalletProjects-notification`)
- 📬 Communication Backbone
  - gRPC-powered notification dispatch
  - Extensible communication channels
  - Event-driven notification strategies

## 🛠 Tech Stack Superpowers

| Category | Technology | Purpose |
|----------|------------|---------|
| Framework | Go Fiber | High-performance web framework |
| Database | PostgreSQL | Robust, ACID-compliant data storage |
| ORM | SQLC | Type-safe, efficient database interactions |
| Containerization | Docker | Consistent, reproducible environments |
| API Protocols | REST, gRPC | Flexible, performant communication |

## 📖 API Documentation

Comprehensive API documentation is available on Postman:

🔗 **Postman Documentation**: [WalletSync API Docs](https://documenter.getpostman.com/view/29238176/2sAYQfDUVr)

### Key Features in Documentation:
- Detailed endpoint descriptions
- Request/response examples
- Authentication guidelines
- Error handling specifications

## 🔍 Getting Started

### Quick Clone
```bash
git clone https://github.com/ArdiSasongko/EwalletProjects-user
git clone https://github.com/ArdiSasongko/EwalletProjects-wallet
git clone https://github.com/ArdiSasongko/EwalletProjects-transaction
git clone https://github.com/ArdiSasongko/EwalletProjects-notification
```
