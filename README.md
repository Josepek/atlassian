Hey...

Jira Scrum Application Docker Compose File and Installation Guide

## Install Docker
The first step to install Jira is to install the Docker application, if you don't know what Docker is and what it does, go here:
``` 
$ curl -sS https://get.docker.com/ | sh
```

After installing Docker, we need to install Docker Compose, Docker Compose is a tool for running files that have multiple containers, with this tool we can run multiple containers in one Docker Compose file.

If you don't know much about Docker Compose, I suggest you read the link below:

```
https://docs.docker.com/compose/
```

Enter the following command to install Docker Compose in your terminal:

```
$ sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
Next, set the correct permissions so that the docker-compose command is executable:

```
$ sudo chmod +x /usr/local/bin/docker-compose
```
After completing the installation of both applications, you can measure the correctness of the installation process by checking their versions.

```
$ sudo docker -v && docker-compose -v
```
You’ll see output similar to this: example!

```
Output
docker-compose version 1.29.2, build 5becea4c
```
