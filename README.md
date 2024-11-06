# docker

1. docker pull mysql (Pull mysql latest image from docker hub)   
   docker pull mysql:9.1.0 (Pull mysql 9.1.0 image from docker hub)
3. docker images (To see all images)
4. docker run --name mysql-latest -e MYSQL_ROOT_PASSWORD=xuv500 -d mysql:latest  (Run docker image)
5. docker ps (To see running containers)
6. docker ps -a (To see containers which are not running but available)
7. docker start mysql-latest (To start container again)
8. docker rm mysql-latest (To delete container. Note: first stop the container before deleting it)
9. 
