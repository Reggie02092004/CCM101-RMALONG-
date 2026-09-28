## Container Lifecycle Commands

### 1. Check Running Containers

```bash
docker ps
```

I used this command to see the Docker containers that are currently running. It also shows details such as the container ID, image being used, current status, and port information.

### 2. Stop the Nginx Container

```bash
docker stop nginx-server
```

This command stops the Nginx container that I created earlier. The container is stopped but is not deleted yet.

### 3. Check the Container Status

```bash
docker ps
```

I used `docker ps` again to check if the Nginx container was still running. Since the container was already stopped, it no longer appeared in the list of active containers.

I also used the following command to display both running and stopped containers:

```bash
docker ps -a
```

This allowed me to confirm that the `nginx-server` container still existed even though it was no longer running.

### 4. Delete the Container

```bash
docker rm nginx-server
```

After stopping the container, I used this command to remove the `nginx-server` container from Docker.

### Screenshot of the Output

<img width="1440" height="852" alt="image" src="https://github.com/user-attachments/assets/d2aed2ba-4d85-4032-b901-d24904a1a25c" />


## Lifecycle Conclusion

From this activity, I learned the basic steps involved in managing a Docker container. I first checked the active containers, stopped the Nginx container, verified its status, and then removed it after it was no longer needed.

This helped me understand that **stopping a container and removing a container are two different actions**. A stopped container can still exist in Docker until it is specifically removed.

