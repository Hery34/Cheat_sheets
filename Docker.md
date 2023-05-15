# CHEAT SHEET FOR DOCKER

-   `docker build`  - Builds an image from a Dockerfile.
-   `docker run`  - Creates a container from an image and starts it.
-   `docker stop`  - Stops a running container.
-   `docker start`  - Starts a stopped container.
-   `docker restart`  - Restarts a running container.
-   `docker remove`  - Removes a stopped container.
-   `docker images`  - Lists all images.
-   `docker pull`  - Pulls an image from a registry.
-   `docker push`  - Pushes an image to a registry.
-   `docker login`  - Authenticates with a registry.
-   `docker logout`  - Logs out of a registry.
-   `docker network create`  - Creates a network.
-   `docker network connect`  - Connects a container to a network.
-   `docker network disconnect`  - Disconnects a container from a network.
-   `docker volume create`  - Creates a volume.
-   `docker volume attach`  - Attaches a volume to a container.
-   `docker volume detach`  - Detaches a volume from a container.
-   `docker volume inspect`  - Inspects a volume.
-   `docker volume ls`  - Lists all volumes.
-   `docker volume rm`  - Removes a volume.
-   `docker ps`  - Lists all running containers.
-   `docker ps -a`  - Lists all containers, including stopped ones.
-   `docker logs`  - Shows the logs for a container.
-   `docker exec`  - Executes a command in a running container.
-   `docker attach`  - Attaches to a running container's stdout/stderr/stdin.
-   `docker kill`  - Sends a SIGKILL to a running container.
-   `docker tag`  - Tags an image with a new name.
-   `docker push`  - Pushes an image to a registry.
-   `docker pull`  - Pulls an image from a registry.
-   `docker search`  - Searches for images on a registry.
-   `docker save`  - Saves an image to a tar archive.
-   `docker load`  - Loads an image from a tar archive.
-   `docker rmi`  - Removes an image.
-   `docker system prune`  - Removes all unused images, containers, and networks.
-   `docker info`  - Displays information about Docker.
-   `docker version`  - Displays the Docker version.

**Dockerfile Instructions**

-   `FROM`  - Specifies the base image to build from.
-   `RUN`  - Runs a command in the build environment.
-   `COPY`  - Copies a file from the host to the container.
-   `ADD`  - Copies a file from the host to the container and extracts it.
-   `ENV`  - Sets an environment variable.
-   `WORKDIR`  - Sets the working directory.
-   `CMD`  - Specifies the command to run when the container starts.
-   `ENTRYPOINT`  - Specifies the command to run when the container starts and cannot be overridden.

**Docker Compose**

-   `version`  - Specifies the version of Docker Compose.
-   `services`  - A list of services to create.
-   `container_name`  - The name of the container.
-   `build`  - The path to the Dockerfile to build the image from.
-   `ports`  - The ports to expose on the host.
-   `volumes`  - The volumes to mount in the container.
-   `environment`  - The environment variables to set in the container.
-   `command`  - The command to run when the container starts.