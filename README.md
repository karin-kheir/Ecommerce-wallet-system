# Ecommerce-wallet-system
A full-stack E-Commerce application with internal wallet system and support for hybrid payments. Users can browse products, add to cart, checkout using either internal wallet balance or external payment methods.
The system implements JWT-based authentication, role-based access control, transaction management, and ACID-compliant wallet transactions.

---

## Features
- User registration & login with JWT authentication
- Role-based access control (ADMIN / CUSTOMER)
- Products and Categories management
- Orders and Checkout system
- Internal wallet:
  - Deposit (Simulation / later integration with external payment)
  - Purchase from wallet
  - Transfer to other users
- Payment strategy:
  - Internal Wallet
  - External Payment Gateway (Card, Bank, PayPal)
- Transaction history & audit logs
- Clean modular architecture (Controller → Service → Repository)
- PostgreSQL integration 

---

## Technologies Used
- Java 17 + Spring Boot
- Spring Security + JWT
- Spring Data JPA
- PostgreSQL
- Maven
- Swagger (optional for API testing)
