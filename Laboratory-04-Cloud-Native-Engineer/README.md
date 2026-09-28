## Mission Overview

In this mission, I learned about **Docker and containerization**, which are commonly used when developing and deploying cloud-based applications. The activity helped me understand how containers are different from Virtual Machines. I also practiced using Docker to download, run, access, stop, and remove an Nginx web server.

## Objectives

The main goals of this activity were to:

* Learn the basic concept of Docker and containerization.
* Understand the main differences between Virtual Machines and containers.
* Check if Docker is properly installed and working.
* Download an Nginx image from Docker Hub.
* Create and run an Nginx container.
* Use port mapping to access the web server through the host machine.
* Practice starting, stopping, checking, and deleting containers.
* Record the commands, results, and important things learned from the activity.

## Docker Commands Used

These are the commands I used while completing the Docker activity.

### Checkpoint 3 – Checking the Docker Environment

First, I checked the Docker version and system information to make sure that Docker was installed and running correctly.

```bash
docker --version
docker info
```

### Checkpoint 4 – Running an Nginx Container

I downloaded the Nginx image and used it to create a container. I also mapped port `8080` on the host machine to port `80` inside the container. After running the container, I used `curl` to check if the web server was responding.

```bash
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
```

### Checkpoint 5 – Managing the Container Lifecycle

For the container lifecycle activity, I checked the running containers, stopped the Nginx container, checked its status, and then removed it.

```bash
docker ps
docker stop nginx-server
docker ps
docker ps -a
docker rm nginx-server
```

## Skills I Learned

After completing the activity, I was able to learn the following:

* Basic concepts of Docker and containerization.
* Differences between Virtual Machines and containers.
* How to download Docker images from Docker Hub.
* How to create and run a container in detached mode.
* How port mapping connects the host machine to a container.
* How to test a web server running inside a container.
* How to check, stop, and remove Docker containers.
* How to organize screenshots and activity files for a GitHub repository.

## Challenges I Encountered

One of the things I found confusing at first was understanding how containers differ from Virtual Machines. I also had to learn how the port mapping works, especially why port `8080` on the host is connected to port `80` inside the Nginx container.

Another thing I had to understand was the difference between **stopping** and **removing** a container. Stopping a container does not delete it, while removing it deletes the container itself. After practicing the commands, I became more comfortable with Docker and understood the basic process of managing containers.

