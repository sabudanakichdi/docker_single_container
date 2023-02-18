# Docker: Single container, Single Image
Created docker image and container to execute simple python script.

### Steps taken:

Step 1: Created a python file: main.py

![main.py](http://url/to/img.png)
 
Step 2: Created Dockerfile with environment parameters to run above python script

![DockerFile](http://url/to/img.png)
 
Step 3: Ran docker build command to build docker image named docker-python-test

![Docker Image Build](http://url/to/img.png)
 
Once successful, to check whether image was created: executed ‘docker images’ to get image list.

![Docker Image List](http://url/to/img.png)
 
Step 4: After successfully creating docker image, next step is to run docker container of the generated image.  execute 'docker run docker-python-test’

![Docker Container Creation and Run](http://url/to/img.png)
 
Output in yellow box, proves the successful execution of python script.

![Docker Container and Output](http://url/to/img.png)

Then, run ‘docker ps -ls’ to see the containers list.

![Docker Container List](http://url/to/img.png)
 

### Reflection:
-	Understood the concept of DevOps tool docker.
-	Learned how to create environment specific to project executions using docker.
-	Understood the relations between images and container.

#### Source code: 
https://github.com/sabudanakichdi/docker_single_container

### Docker image repo: 
https://hub.docker.com/repository/docker/sabudanakichdi1/docker-python-test/general


