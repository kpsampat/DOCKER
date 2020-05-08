# DOCKER

## TUTORIALS 
https://www.docker.com/101-tutorial
## Docker on Alpine Linux
https://docs.genesys.com/Documentation/System/8.5.x/DDG/InstallationofDockeronAlpineLinux

docker run -it <mage-id> /bin/bash
hostname ( run inside the container to allocate the identity to the container )
  
docker ps

docker commit < containe ID>

docker stop < container ID>

docker start <container ID>

build your docker file using 
docker compose
docker build -t getting-started .


Remember the -d and -p flags? We're running the new container in "detached" mode (in the background) and creating a mapping between the host's port 3000 to the container's port 3000. Without the port mapping, we wouldn't be able to access the application.

docker push docker/getting-started
docker build -< /home/kishan/Downloads/kpdocker/Dockerfile.yml 
docker exec -it containerid /bin/bash
