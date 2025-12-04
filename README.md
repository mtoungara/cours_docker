# cours_docker

# Pull an image

docker pull ubuntu

# Run a container

docker run -it ubuntu bash

$ docker run --name some-wordpress -p 8080:80 -d wordpress

# List containers

docker ps -a

# Build an image from Dockerfile

docker build -t myapp .

# Stop and remove containers

docker stop <container_id>

docker rm <container_id>
