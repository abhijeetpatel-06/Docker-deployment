# Troubleshooting

## Port Already Used
lsof -i :8080

## Remove All Containers
docker rm -f $(docker ps -aq)

## Remove Unused Images
docker image prune -a