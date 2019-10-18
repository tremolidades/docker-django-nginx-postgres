# docker-django-nginx-postgres
test for deploy django on docker with docker compose

## Shell Accesing

### Nginx
docker exec -ti nginx bash

### Web
docker exec -ti web bash

### Database
docker exec -ti db bash

## Logs

### Nginx
docker-compose logs nginx
### Web
docker-compose logs web
### DB
docker-compose logs db


# EXEC:

docker-compose build
docker-compose up -d
docker-compose stop
docker-compose start
