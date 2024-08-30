# Steps:

#### Assuming we have Source Code, create a Dockerfile

#### Create a Docker Image using the Dockerfile. Use below command for the same.

        docker build -t <image-name>:<tag> .

#### Log in to DockerHub (Docker Registry) using below command

        docker login

#### Push the same Image to the DockerHub (Docker Registry). Use below command for the same.

        docker push <image-name>:<tag>

#### Run docker container using below command

        docker run -itd -p <container-port>:<host-port> <image-name>:<tag> 
