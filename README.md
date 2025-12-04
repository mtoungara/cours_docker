# cours_docker

# Pull an image

docker pull ubuntu

# Run a container

docker run -it ubuntu bash

$ docker run --name some-wordpress -p 8080:80 -d wordpress

$ docker exec -it some-mysql bash

$ sudo docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=your_secret_password -p 3307:3306 -d mysql:latest

# List containers

docker ps -a

# Build an image from Dockerfile

docker build -t myapp .

# Stop and remove containers

docker stop <container_id>

docker rm <container_id>
