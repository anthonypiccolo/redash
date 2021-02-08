# redash
Redash Docker Instance

1. Clone repo locally
2. Start Docker
3. Ensure the `docker-compose.yml` config is pointing to the env file and postgresql folder exists
4. Run `docker-compose run server create_db`. If having issues run, `docker-compose run --rm server create_db`. See the list of containers running using `docker ps -a`. Removing running containers using `docker rm $(docker ps -a -q)` or use the Docker extension in VS Code.
5. Run `docker-compose up -d`
6. Visit `localhost:5000`
7. To stop run `docker-compose stop`
