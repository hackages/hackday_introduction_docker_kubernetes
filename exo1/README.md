# Let's play with the CLI !
## Introduction to the Docker CLI

### Start and stop containers

In this exercice, we would like to create a container, see it running and then kill it.

For this, you'll need to use the following command

```
docker pull .. 
docker run ..
docker stop .. 
docker pause ..
docker start ..
docker ps
docker ls
```

You can use the base image of Alpine or CentOS. 

### Inspect logs and data persistence through volumes

Using the command docker logs, try to get some logs from your container. 
Then find a way to bind the log folder with a log folder created before on your local machine. 

### Port mapping 

In this exercice, try to contact an apache container or server by mapping port using the below command. 

``` docker run .. ```

### Passing environment variables

Pull the image : docker pull josue549/hello-env and find a way to change the ENV variable when running. 

Then log on the container and look after the env variable

### Execute commands inside your container

Try to start /bin/sh in your container. 

