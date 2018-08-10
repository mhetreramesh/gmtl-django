## Get me the look backend app

### What things include in this project?
1. Python `3.6`
2. Postgress `Latest`
3. Nginx `Latest`
4. Redis `Latest`

###### While doing docker up, it will automatically install other python dependencies from requirements.txt file

### How to start
1. Make sure you have `docker` & `docker-compose` installed on your local
2. Clone this repo on your machine
3. First run `make build` inside root directory.
4. Then run `make up` to start up the project for first time.
5. Project should be accessible on `localhost:8000`

Checkout the [commands](#commands) for more usage.


### Commands
To use this project efficiently, below commands are available:

1. `make up` to build the project and starting containers.
2. `make build` to build the project.
3. `make start` to start containers if project has been up already.
4. `make stop` to stop containers.
5. `make shell-web` to shell access web container.
6. `make shell-db` to shell access db container.
7. `make shell-nginx` to shell access nginx container.
8. `make logs-web` to log access web container.
9. `make logs-db` to log access db container.
10. `make logs-nginx` to log access nginx container.
11. `make collectstatic` to put static files in static directory.
12. `make log-web` to log access web container.
13. `make log-db` to log access db container.
14. `make log-nginx` to log access nginx container.
14. `make restart` to restart containers.
