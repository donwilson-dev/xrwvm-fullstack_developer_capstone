# fullstack_developer_capstone

## Project Overview

This project is a Full Stack Developer Capstone application built as part of the IBM Full Stack Software Developer Professional Certificate.

The application is a dealership review portal that allows users to:
- View dealerships across the United States
- Filter dealerships by state
- View dealership reviews
- Register and log in as authenticated users
- Submit reviews for dealerships
- Analyze review sentiment using a cloud-based sentiment analyzer service

---

## Technologies Used

### Frontend
- React
- HTML
- CSS
- Bootstrap
- JavaScript

### Backend
- Django
- Node.js
- Express

### Databases
- MongoDB
- SQLite

### DevOps / Cloud
- Docker
- Kubernetes
- IBM Cloud Code Engine
- GitHub Actions CI/CD

---

## Features

- User authentication and session management
- Dealer listing and filtering by state
- Dealer review system
- Sentiment analysis for reviews
- Dynamic React frontend
- REST API integration
- Dockerized backend services
- Kubernetes deployment support
- CI/CD workflow integration

---

## Microservices

### Django Application
Provides:
- Frontend rendering
- Authentication
- Proxy services
- Car make/model management

### Dealership and Reviews Service
Express + MongoDB microservice providing:
- Dealer data
- Review data
- Review submission endpoints

### Sentiment Analyzer Service
Cloud-hosted sentiment analysis service used to evaluate review sentiment.

---

## Project Architecture

Browser
→ React Frontend
→ Django Application
→ Django Proxy Services
→ Express/MongoDB Microservices
→ Sentiment Analyzer Service

---

## Author

Donald Wilson

IBM Full Stack Software Developer Professional Certificate Capstone Project
