# Dockerized Wordpress

## Deploy steps

1. Rename `.env.example` file to `.env` and change values to your own configuration.
2. Run `docker network create link.ravf.external`.
3. Run `docker compose up -d --force-recreate` to deploy wordpress and its maria database.
4. Run `docker compose logs wordpress` to check the wordpress service logs.
5. Run `docker compose logs mariadb` to check the wordpress service logs.