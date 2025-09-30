# Docker Command
## Docker Image
* docker pull [Image Name]
* docker run [options] [ชื่อ Image]
* docker build -t [Tag Name] .
* docker images
* docker rmi [Image ID]

## Docker Container
* docker ps
* docker start [Container ID]
* docker stop [Container ID]
* docker rm [Container ID]
* docker exec -it [Container ID]
* docker logs [Container ID]
* docker inspect [Container ID]
* docker stats
* docker cp [Container Id]:[Source Path] [Destination Path]

## Container Registry
* docker login
* docker tag [SOURCE_IMAGE]:[TAG_NAME]
* docker push [CONTAINER_REGISTRY_URL]/[IMAGE_NAME]:[TAG_NAME]
* docker logout

## Volume
* docker volume ls
* docker run -v ${PWD}:/app [Image Name]
* docker run -v [Volume Name]:/app [Image Name]
* docker run -v /app [Image Name]
* docker volume prune
* docker volume rm [Volume Name]
* docker system df -v

