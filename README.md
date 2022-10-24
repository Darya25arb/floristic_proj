# Floristic Shop: Dockerized Django along with Nginx and PostgreSQL

Docker can be used to deploy most stacks with Nginx and Postgres.

## Installation

Your system must have [docker-compose](https://docs.docker.com/compose/install/) to follow along.

```bash
docker-compose build
docker-compose up
```
You would be able to access

[localhost:8008](http://localhost:8008/)

## Usage
stop the container
```bash
docker-compose down
```
drop to django shell
```bash
docker-compose exec web python manage.py shell
```
more at [here](https://docs.docker.com/get-started/overview/)
