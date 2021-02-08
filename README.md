# redash
Redash Docker Instance

1. Clone repo locally
2. Start Docker
3. Ensure the `docker-compose.yml` config is pointing to the env file and postgresql folder exists
4. Run `docker-compose run server create_db`
5. Run `docker-compose up -d`
6. Visit `localhost:5000`
7. To stop run `docker-compose stop`
