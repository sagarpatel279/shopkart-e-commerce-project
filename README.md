# E-Commerce Platform (Microservices Architecture)

This is a backend e-commerce application built using Spring Boot microservices, Docker, OAuth2, Stripe API, Redis, and more.

## 🔧 Services

| Service           | Description                                 | GitHub Link                                           |
|-------------------|---------------------------------------------|--------------------------------------------------------|
| 🛍 Product Service | Manages product catalog                    | [product-service](https://github.com/sagarpatel279/shopkart-product-catalog-service) |
| 🔐 Auth Service    | Self User Serive with JWT tokens          | [auth-service][self-service](https://github.com/sagarpatel279/shopkart-authentication-service) |
| 🔐 Auth Service2    | Handles user login/signup and JWT tokens | [auth-service][OAuth2](https://github.com/sagarpatel279/shopkart-authorization-oauth2) |
| 💳 Payment Service | Integrates with Stripe for payments       | [payment-service](https://github.com/sagarpatel279/shopkart-payment-service) |

## 🧰 Tech Stack
- Java, Spring Boot, Spring Security
- Redis, MySQL, Docker, OAuth2
- Stripe API, RabbitMQ, GitHub Actions
