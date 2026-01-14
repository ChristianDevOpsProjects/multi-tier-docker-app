# Multi-Tier Docker App

A beginner-friendly multi-tier application demonstrating **Docker, Docker Compose, and containerized services**.

## Tech Stack
- Frontend: HTML + Nginx
- Backend: Node.js (Express)
- Database: PostgreSQL
- Docker & Docker Compose

## Architecture
Browser
↓
Frontend (Nginx)
↓
Backend (Node.js)
↓
Database (PostgreSQL)

bash
Copy code

## How to Run

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/multi-tier-docker-app.git
cd multi-tier-docker-app
Build and run containers:

bash
Copy code
docker-compose up --build
Open in browser:

Frontend: http://localhost:8080

Backend API: http://localhost:5000

Click "Call Backend" in the frontend to see database data.
