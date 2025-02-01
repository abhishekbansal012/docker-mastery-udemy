# Important Commands in DOCKER

## View docker version
docker version

## View docker info
docker info

## View docker commands available (basic)
docker

## Create a new container
docker container run --publish 80:80 nginx

## Create a new container Detached Mode
docker container run --publish 80:80 --detach nginx

## Create a new container Detached Mode with a custom name
docker container run --publish 80:80 --detach --name webhost nginx

## List all containers RUNNING
docker container ls

## List all containers ALL
docker container ls -a

## Stop a container using its id
docker container stop <ID>

## View docker logs
docker container logs <ID>

## Remove docker containers 
### we can give multiple ids here 
docker container rm <ID> <ID> <ID>
eg - docker container rm bbdd2a86cd18 d501d7e10c96 67e7c01c7b9f


