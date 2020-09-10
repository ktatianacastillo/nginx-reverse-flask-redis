# nginx-reverse-flask-redis

The docker compose has 4 containers

1. nginx proxy
    if the root is / redirect to ginix with static files
    if the root is /app/ redirect to flask with redis 
2. flask
3. redis
4. gninx with static files

## Run It

`docker-compose up -d`
