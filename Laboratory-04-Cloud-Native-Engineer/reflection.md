## 1. How does the boot time and setup process of a Docker container compare to installing an operating system on a Virtual Machine?

Docker containers are generally quicker to set up than Virtual Machines. With a VM, we have to prepare and start an entire operating system before using it for an application. In Docker, we can download an existing image and start a container with just a few commands. Because containers do not need a complete operating system for each instance, they can start faster and normally require fewer system resources.

## 2. Why is port mapping (`-p 8080:80`) necessary when running a web server inside a container?

Port mapping allows the host computer to communicate with a service running inside the Docker container. In `-p 8080:80`, the `8080` represents the port on the host machine, while `80` is the port where Nginx is listening inside the container. Because of this connection, I can open the Nginx server through `http://localhost:8080`.

## 3. What happens to the data inside a container when you use the `docker rm` command?

The `docker rm` command deletes the container from Docker. Any files or data that were stored only inside that container may also be deleted. If the data needs to remain available even after the container is removed, it should be stored using a Docker volume or another storage solution.

## 4. How do you think containerization changes the way software developers and IT operations teams work together (DevOps)?

Containerization can make collaboration between developers and IT operations easier because the application, dependencies, and configuration can be packaged together. This means developers can test the same container setup that will later be used for deployment. It can help reduce environment-related issues and make the process of testing and deploying applications more consistent.

## 5. How is your GitHub portfolio evolving?

My GitHub portfolio is slowly becoming more complete and organized as I add each laboratory activity. Instead of just uploading answers, I am also including my research, commands, screenshots, documentation, and reflections. This allows me to keep a record of what I have learned throughout the cloud computing activities. In the future, the repository can also serve as a portfolio that shows the skills and experience I gained from these activities.

