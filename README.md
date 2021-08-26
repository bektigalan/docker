# How to Docker

## how to run docker
docker run -itd -p 5000:8080 (image ID)

## how to run shell
docker exec -it (container ID) /bin/bash or /sh

## how to delete image
docker rmi (image ID)

## how to stop running container
docker stop (container ID)

## how to copy files to running container
docker cp (source) (container ID):/(destination)