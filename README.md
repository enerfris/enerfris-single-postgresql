# enerfris-single-postgresql

Quickstart's Docker Compose PostgreSQL with PgAdmin

## Requirements

- Docker compose

## Steps

### 1. Clone the repository

```shell
git clone https://github.com/enerfris/enerfris-single-postgresql
cd enerfris-single-postgresql
```

### 2. Set environment variables

Create a `.env` from `.env.example` file in the root folder with all environment variables, this variables will be used by the containers, it need to be reached by `docker-compose.yml` file.

After type and run the command go to `localhost:${PG_ADMIN_PORT}`