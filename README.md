# pycrawler-1

> PyCrawler 1: Python async web crawler with link graph and content extraction

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Python, Django, MySQL, Celery, Redis

## 🏗️ Architecture
Three-tier architecture: Python, Django backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/pycrawler-1
cd pycrawler-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
