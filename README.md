# NexaShop — Docker Setup 🐳

One command to run the entire NexaShop stack locally.

## Prerequisites
- Docker Desktop or Colima
- Docker Compose

## Quick Start

```bash
git clone https://github.com/kusamdinesh/nexashop-docker.git
cd nexashop-docker
docker compose up --build
```

## Services

| Service | URL | Description |
|---------|-----|-------------|
| Frontend | http://localhost:4200 | Angular app |
| Backend | http://localhost:8000 | FastAPI |
| API Docs | http://localhost:8000/docs | Swagger UI |
| PostgreSQL | localhost:5432 | Relational DB |
| MongoDB | localhost:27017 | NoSQL DB |
| Redis | localhost:6379 | Cache |

## Default Login

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@nexashop.com | Admin123! |
| Manager | manager@nexashop.com | Manager123! |
| Staff | staff@nexashop.com | Staff123! |

## Related Repositories

- [nexashop-backend](https://github.com/kusamdinesh/nexashop-backend)
- [nexashop-frontend](https://github.com/kusamdinesh/nexashop-frontend)