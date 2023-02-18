# Docker: Single Image, Single Container
Created docker image and container to execute simple python script.

### Steps taken:

Step 1: Created a python file: main.py

![main.py](https://github.com/sabudanakichdi/docker_single_container/blob/main/documentation/images/main-file.png)
 
Step 2: Created Dockerfile with environment parameters to run above python script

![DockerFile](https://github.com/sabudanakichdi/docker_single_container/blob/main/documentation/images/dockerfile.png)
 
Step 3: Ran docker build command to build docker image named docker-python-test

![Docker Image Build](https://github.com/sabudanakichdi/docker_single_container/blob/main/documentation/images/docker-image-build.png)
 
Once successful, to check whether image was created: executed ‘docker images’ to get image list.

![Docker Image List](https://github.com/sabudanakichdi/docker_single_container/blob/main/documentation/images/docker-image-list.png)
 
Step 4: After successfully creating docker image, next step is to run docker container of the generated image.  execute 'docker run docker-python-test’
 
Output in yellow box, proves the successful execution of python script.

![Docker Container and Output](https://github.com/sabudanakichdi/docker_single_container/blob/main/documentation/images/docker-output.png)

Then, run ‘docker ps -ls’ to see the containers list.

![Docker Container List](https://github.com/sabudanakichdi/docker_single_container/blob/main/documentation/images/docker-container-list.png)
 

### Reflection:
-	Understood the concept of DevOps tool docker.
-	Learned how to create environment specific to project executions using docker.
-	Understood the relations between images and container.

#### Source code: 
https://github.com/sabudanakichdi/docker_single_container

### Docker image repo: 
https://hub.docker.com/repository/docker/sabudanakichdi1/docker-python-test/general


