# Docker Learning Project

## Build Docker Image

docker build -t docker-learning .

## Run Container

docker run -d -p 8080:80 docker-learning

## Docker Compose

docker compose up -d

## Stop Containers

docker compose down


This Repositry contain this kind of the Structure


docker-learning/
│
├── app/
│   ├── index.html
│   ├── style.css
│   └── Dockerfile
│
├── docker-compose.yml
├── .dockerignore
├── .env
├── README.md
│
├── volumes/
├── logs/
│
└── docs/
    ├── docker-basics.md
    ├── docker-commands.md
    ├── docker-networking.md
    ├── docker-volumes.md
    ├── docker-compose.md
    └── troubleshooting.md