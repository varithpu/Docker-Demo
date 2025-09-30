# Docker Network
## Basic Commands
* docker network ls
* docker run --network=host [Image Name]
* docker network create [Network Name]
* docker network create -d bridge [Network Name]
* docker network connect [Network Name] [Container Name]
* docker network inspect [Network Name]