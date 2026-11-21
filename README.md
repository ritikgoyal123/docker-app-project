Docker App Project
Overview
Build and run a Docker container locally using Nginx.

Files
Dockerfile
index.html
Commands
docker build -t docker-project .

docker run -d -p 8080:80 --name docker-container docker-project

Result
Application successfully served from a Docker container.
