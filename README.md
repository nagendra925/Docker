# Docker
FROM      : To pull the base image
RUN 	  : to execute commands
CMD       : to provide default for an executing container
ENTRYPOINT: to configure a container that will run as an executable 
WORKDIR   : to sets the working directory 
COPY      : to copy a directory from your local machine to the docker container
ADD       : to copy files and folders from your local machine to docker container
EXPOSE    : inform docker that the container listen onthe specided network port at runtime
ENV       : to set environmental variable 
