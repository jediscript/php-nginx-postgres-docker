# Dockerized Lumen-nginX-PostgreSQL

> **Note:** This is for local development use only. To use this in Production, please consult with our DevOps team

### Requirements

1. Install Docker
2. Install Docker Compose

### How-to

1. Copy all your lumen application files inside `lumen` directory
2. Run `docker-compose up -d` in root directory of this. Where `docker-compose.yml` is located
3. See `http://localhost:8080` to check if your application is running.

### Contributing

Contribution is always welcome. This is an ongoing improvement local development setup.

Please submit a PR. Thank you.

### Notes

This is running PHP 7.2 - FPM. See `/image/php/Dockerfile` for more details of the PHP web server.
