#Day 01 - Docker Basics

##Date 2026 - 02 - 02

Goal for Today
Understand Docker Images, containers & build first image

Concepts learned
Overview of Docker
Virtualization tool & it helps to easily setup environment across all landscape (as the app along with its services and configurations are packaged)
Difference between VMs and Docker
Docker has its own OS but no Kernel & Kernel helps for communication with system hardware
Whereas, VM has its own OS and Kernel -> so it takes time to start and is huge in size as well
What's an image, container, dockerfile & dockerhub
Docker Image acts as a blueprint file and has everything (App, services, Light OS & all configuration files inside)
Container is the running docker image
Dockerfile has instructions to build an image
DockerHub is the place where images are stored Comparison: Docker image is the recipe & docker container is the dish made out of it
Hands-On Done
Used online docker for learning: https://labs.play-with-docker.com/

Commands used

docker pull (Download image from hub)

docker run (Create & start container)

docker ps (Check the container running in system)

docker stop (Stop the containers)

docker images (list the images in system)

Ran hello-world container docker run hello-world (If not available pulls from dockerhub)

Ran a web server in a port by creating a container docker run -d -p 8080:80 nginx
