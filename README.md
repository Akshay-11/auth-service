# Sinatra authentication microservice

## How to build and run container

1. `docker build -t auth-service .`
2. `docker run --env-file .env -p 5002:5002 auth-service:latest`
