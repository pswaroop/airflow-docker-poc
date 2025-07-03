# airflow-docker-poc

Running Airflow in Docker documentation:
https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html

docker compose up

docker compose down

Command to retrieve list of containers in docker:
docker container ls

Command to retrieve IP Address/HOST :
docker inspect <container-id> 

Command to list all containers in docker:
docker ps

Command to check pip dependencies installation on docker containers:
docker exec -u <user-name> -it <container-name> pip list