# user-management-with-api

User management API built on top of a Postgres database with FastAPI and JWT authentication, dockerized with multi-stage builds, bcrypt password hashing, pagination, CORS, rate limiting, full test coverage (pytest), and Swagger UI. Ready to deploy in development, staging, or production.

## Technologies

- FastAPI
- Postgres
- SQLAlchemy
- JWT
- Uvicorn
- Docker Compose (local/prod/stage environments).

## Requirements

- Docker
- docker-compose
- Python 3.6+ **To use without docker**

## Useful commands

```pwsh
docker-compose -f local.yml build
```

```pwsh
docker-compose -f local.yml up -d
```

```pwsh
pytest -vvs src/tests/
```

## Imagery

![](./screenshots/ui.png)
