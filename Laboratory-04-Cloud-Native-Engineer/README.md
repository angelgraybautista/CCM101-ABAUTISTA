# Laboratory 04 – The Cloud-Native Engineer

## Mission Overview

Through this hands-on experimentation in the lab, cloud-native engineering was introduced as the primary topic. It highlighted the major differences between Virtual Machines and Containers. With KillerCoda Playground as my platform, I was able to get myself familiar and practice the basic command-line functionalities of Docker. In the process, I was able to successfully install a web server using Nginx in a container environment, which served as one of the main lab tasks to be accomplished. Alongside that, I also gained insight into the container life cycle management and was proficient in noting down the operations through Markdown documents.

## Objectives

* Differentiate between Virtual Machines and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI commands.
* Pull, run, manage, and terminate an Nginx container.
* Document container operations using Markdown.
* Organize and update my GitHub Cloud Computing Portfolio.

## Docker Commands Executed

### Check Docker Installation and Status

```bash
docker --version
docker info
```

### Pull and Run Nginx

```bash
docker pull nginx
docker run -d --name my-nginx -p 8080:80 nginx
curl http://localhost:8080
```

### Manage the Container Lifecycle

```bash
docker ps
docker stop my-nginx
docker ps
docker ps -a
docker rm my-nginx
```

## Skills Learned

* I learned the basic differences between Virtual Machines and Containers.
* I learned how to check Docker installation and status.
* I learned how to pull an image and run a container.
* I learned how port mapping allows access to a web server inside a container.
* I learned how to stop, verify, and remove a Docker container.
* I improved my skills in writing technical documentation using Markdown and organizing files in GitHub.

## Challenges Encountered

One of the problems that I had was figuring out the different Docker commands and how they can affect a container.
In addition, I wanted to get a better idea about what a port mapping really does, more specifically, I was curious to know at least the connection logic behind how port 8080 of the host machine gets associated with port 80 of the Nginx container.
One more difficulty was to ensure that we actually had a running container and the screenshots displayed exactly what we had done. In the end, by using all the instructions one after another and getting some guidance if necessary I was able to get some insights about Docker usage and managing containers.
