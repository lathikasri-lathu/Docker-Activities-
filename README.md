DOCKER- Docker is a platform for containerize the application.

CONTAINER-
   container is a bundle of application ,application libraries required to run your application and the minimum system dependencies.

Why is container is lightweight?

Containers are lightweight because they use a technology called containerization,which allows them to share the host operating system's and libraries.while still providing isolation of application and depdencies.

TO RUN A HELLO-WORLD IMAGE FROM DOCKER HUB USING THIS STEPS:
1.INSTALL DOCKER -
     You can check whether docker is installed or not using the following commands:docker --version

2.Pull the "hello-World" image
   
	
   Pull the image by running:docker pull hello-world.


3.Run the "hello-world"container
   
Using docker run command:docker run hello-world.

DOCKER CREATES A CONTAINER FROM THE "hello-world"image.

It run simple application that prints a "hello from Docker!"message and exists.

You'll will see the output like this:

hello from Docker!



