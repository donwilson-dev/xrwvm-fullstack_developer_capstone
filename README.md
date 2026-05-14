# Best Cars Dealership Review Platform

Full Stack dealership review and vehicle inventory application built as part of the IBM Full Stack Software Developer Professional Certificate.

This project evolved beyond the original course requirements into a portfolio-focused full stack application featuring enhanced UI/UX styling, frontend refinements, microservice integration, and modern Git workflow practices.

---

# Project Overview

Best Cars is a dealership review platform that allows users to:

- View dealerships across the United States
- Filter dealerships by state
- View dealership reviews
- Register and authenticate users
- Submit dealership reviews
- Analyze review sentiment using a cloud-hosted sentiment analyzer
- Search dealership vehicle inventory
- Filter vehicles by:
  - Make
  - Model
  - Year
  - Mileage
  - Price

---

# Technologies Used

## Frontend
- React
- JavaScript
- HTML
- CSS
- Bootstrap

## Backend
- Django
- Node.js
- Express

## Databases
- MongoDB
- SQLite

## DevOps / Cloud
- Docker
- Kubernetes
- IBM Cloud Code Engine
- GitHub Actions CI/CD

---

# Features

- User authentication and session management
- Dealer listing and filtering
- Dealer review system
- Vehicle inventory search
- Vehicle filtering system
- Review sentiment analysis
- Dynamic React frontend
- REST API integration
- Dockerized backend services
- Kubernetes deployment support
- CI/CD workflow integration

---

# UI / UX Enhancements

The original IBM capstone project was extended with a custom UI enhancement initiative focused on improving usability, frontend consistency, and portfolio-level presentation.

Enhancements include:

- Unified blue/white application theme
- Responsive navigation styling
- Modernized dealership layouts
- Improved review panel styling
- Enhanced login page UI
- Reusable CSS component styling
- Interactive hover effects and transitions
- Improved spacing and visual hierarchy
- Styled Search Cars inventory page
- Refined About and Contact pages
- Portfolio-focused frontend polish

---

# Microservices Architecture

## Django Application
Provides:
- Frontend rendering
- Authentication
- Proxy services
- API routing
- Car make/model management

## Dealership & Inventory Service
Express + MongoDB microservice providing:
- Dealer data
- Review data
- Vehicle inventory data
- Review submission endpoints

## Sentiment Analyzer Service
Cloud-hosted sentiment analysis service used to evaluate customer review sentiment.

---

# Project Architecture

Browser  
→ React Frontend  
→ Django Application  
→ Django Proxy Services  
→ Express/MongoDB Microservices  
→ Sentiment Analyzer Service  

---

# Git Workflow

Development enhancements were implemented using a dedicated feature branch workflow:

- `main`
  - Stable production-style branch

- `enhancements`
  - Active UI/UX enhancement branch

Changes were tested locally before being merged into the main branch through GitHub pull requests.

---

# Local Development

## Clone Repository

```bash
git clone <repo-url>
