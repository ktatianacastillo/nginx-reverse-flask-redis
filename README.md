# nginx-reverse-flask-redis

The docker compose has 4 containers

1. nginx proxy
1.1 if the root is / redirect to nginx with static files
1.2 if the root is /app/ redirect to flask with redis 
2. flask
3. redis
4. gninx with static files

## Run It

`docker-compose up -d`
