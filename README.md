# pulsecheck
Uptime &amp; network monitoring service with an AI agent that diagnoses incidents

## Running locally

Requirements: [Docker](https://www.docker.com/products/docker-desktop/)

1. Create your environment file and set a password:
   ```bash
   cp .env.example .env
   ```
2. Start the services:
   ```bash
   docker compose up --build
   ```
3. Open http://127.0.0.1:8000/docs