# Recipe API

A Dockerized Django REST API with recipe, user, and shared core modules.

## Develop locally

The development services are defined in `docker-compose.yml`. The Django project lives in `app/`, with separate `recipe/`, `user/`, and `core/` packages. `docker-compose-deploy.yml` and `proxy/` contain deployment configuration.
