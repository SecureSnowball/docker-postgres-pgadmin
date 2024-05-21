# Docker Postgres & PgAdmin

Setup Postgres & PgAdmin using Docker

## Software Requirements

- Docker

## How to setup

- Linux only: Create `data/pgadmin` folder using `mkdir -p data/pgadmin`.
- Linux only: Update permissions for pgadmin folder using `sudo chown -R 5050:5050 data/pgadmin`
- Copy `.env.example` to `.env`.
- Update values in `.env`.
- Run `docker compose up -d` to start.
- Open `http://localhost:8000` (Change port according to PGADMIN_PORT) and follow next steps

## Common commands

- Start services: `docker compose up -d`.
- Stop services: `docker compose down`.
- Check logs: `docker compose logs -f`.
