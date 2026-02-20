# Task 1 — Explore the API

- Started services: `docker compose --env-file .env.docker.secret up --build`
- Swagger UI: http://127.0.0.1:42001/docs

Checks:
- GET /items without API key -> 401 Unauthorized
- GET /items with API key -> 200 OK