# Fitness Application

A microservice-based fitness tracking application built using Spring Boot, Spring Cloud, React, Docker, and MongoDB.

## Architecture

Microservices included:

- User Service
- Activity Service
- AI Recommendation Service
- API Gateway
- Eureka Discovery Server
- Config Server
- React Frontend

## Technologies Used

### Backend
- Java
- Spring Boot
- Spring Cloud
- Spring Security
- Eureka
- API Gateway
- MongoDB
- RabbitMQ

### Frontend
- React
- Vite

### DevOps
- Docker
- Docker Compose

## Features

- User registration/login
- Activity tracking
- AI-based recommendations
- API Gateway routing
- Service discovery
- Centralized configuration

## Project Structure

```text
activityservice/
aiservice/
configserver/
eureka/
gateway/
userservice/
fitness-app-frontend/
```

## Running Backend Services

Run each service individually:

```bash
mvn spring-boot:run
```

## Running Frontend

```bash
cd fitness-app-frontend
npm install
npm run dev
```

## Docker Support

```bash
docker-compose up --build
```

## Environment Variables

Do not store API keys directly in code.

Example:

```env
GEMINI_API_KEY=your_api_key
```

## Author

Harshal Patil