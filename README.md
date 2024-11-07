# docker

1. docker pull mysql (Pull mysql latest image from docker hub)   
   docker pull mysql:9.1.0 (Pull mysql 9.1.0 image from docker hub)
3. docker images (To see all images)
4. docker run --name mysql-latest -e MYSQL_ROOT_PASSWORD=xuv500 -d mysql:latest  (Run docker image)   
   docker run --name mysql-latest -p 3306:3306 -e MYSQL_ROOT_PASSWORD=xuv500 -d mysql:latest a9bbd63e508f7a4a004593ba7671bbeefef2ba5cb0196d2e046e0e4c70bce17c (Run docker container on host port 3306)
5. docker ps (To see running containers)
6. docker ps -a (To see containers which are not running but available)
7. docker start mysql-latest (To start container again)
8. docker rm mysql-latest (To delete container. Note: first stop the container before deleting it)
9. docker inspect mysql-latest (To get the information about container)
10. docker logs mysql-latest (To check the logs of the container)
11. docker exec -it mysql-latest mysql -u root -p (To access the MySQL server inside a Docker container, you can use the following command)
    docker exec -it: This command allows you to run a command inside a running container. The -it flags provide an interactive terminal session.
    <container_name>: Replace this with the name of your MySQL container. You can find the name using docker ps.
    mysql -u root -p: This command starts the MySQL client. You'll be prompted for the root password you set when creating the container.
12. 
