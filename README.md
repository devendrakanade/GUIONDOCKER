# GUIONDOCKER
RUN GUI APPLICATION OVER DOCKER CONTAINER

📌 GUI container on the Docker

🔅 Launch a container on docker in GUI mode

🔅 Run any GUI software on the container

Step 1: CREAT DOCKER REPO & INSTALL DOCKER

Step 2: CREATE DIR AND START DOCKER
1] create directory : mkdir <dir_name>
2] open directory : cd <dir_name>
3] start docker : systemctl start docker
4] status docker : systemctl status docker

Step 3: CREATE DOCKERFILE
> vi Dockerfile

Step 4: BUILD DOCKER IMAGE
> docker build -t <img_name> .
> 
TO Check: > docker images

Step 5: LAUNCH FIREFOX
> docker run -it --env="DISPLAY" --net=host --name firefox <img_name>
