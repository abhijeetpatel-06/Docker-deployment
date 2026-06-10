# Docker Commands

## Images
docker images
docker pull nginx
docker build -t myapp .

## Containers
docker ps
docker run nginx
docker stop container_id
docker rm container_id

## Logs
docker logs container_id

## Execute
docker exec -it container_id bash