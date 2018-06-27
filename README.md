# Dockerized Lumen/PHP development

> **Note:** This is for local development use only. To use this in a production environment, please consult with our DevOps team.

### Requirements

1. Install [Docker](https://www.docker.com/community-edition)
2. Install [Docker Compose](https://docs.docker.com/compose/)

### How-to

1. Copy all your lumen application files to `/lumen` directory
2. Run `docker-compose up -d` in the root directory. Where `docker-compose.yml` is located
3. Access [localhost](http://localhost:8080) in your browser to see if your Lumen app is running.

> **Tip:** create a fresh Lumen app using instructions [here](https://lumen.laravel.com/docs/5.6#installing-lumen) for new projects

### Database Management
- Using [Adminer](https://www.adminer.org/) as a tool to manage the PostgreSQL database
- Use the default credentials (can be changed) found in `./docker-compose.yml` to connect

### Contributing

Contribution is always welcome. This is an ongoing improvement for local PHP/Lumen development setup.

Please submit a pull request for your contribution. Thank you.

### Note

- This is running PHP 7.2 - FPM. See `/image/php/Dockerfile` for more details of the PHP web server.

- Tested to work on Lumen v5.6
