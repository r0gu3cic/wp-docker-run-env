# Docker cheat sheet

## Delete all docker images

`docker rmi -f $(docker images -aq)`  

## Delete literally everything except volumes

`docker system prune -a`  

## Delete all volumes

`docker volume prune -a`  
