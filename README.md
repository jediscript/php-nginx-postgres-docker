# Linux, Nginx, Postgres development using Docker

> **Note:** This is for local development use only.

### Requirements

1. Install [Docker](https://www.docker.com/community-edition)
2. Install [Docker Compose](https://docs.docker.com/compose/)

### How-to

1. Copy all your lumen application files to `/lumen` directory or symlink your project in it. Example: `ln -s /path/to/application/directory lumen`
2. Run `docker-compose up -d` in the root directory. Where `docker-compose.yml` is located
3. Access [localhost](http://localhost:8080) in your browser to see if your Lumen app is running.

> **Tip for Lumen micro-framework:** create a fresh Lumen app using instructions [here](https://lumen.laravel.com/docs/5.6#installing-lumen) for new projects

### Database Management
- Using [Adminer](https://www.adminer.org/) as a tool to manage the PostgreSQL database

### Contributing

Contribution is always welcome. This is an ongoing improvement for local PHP development setup.

Please submit a pull request for your contribution. Thank you.

### Note

- This is running PHP 7.2 - FPM. See `/image/php/Dockerfile` for more details of the PHP web server.

- Tested to work on Lumen v5.6 micro-framework
