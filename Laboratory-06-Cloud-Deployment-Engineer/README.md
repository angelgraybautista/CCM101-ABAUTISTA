# Mission 6: The Cloud Deployment Engineer

## Mission Overview

In this laboratory activity, I deployed a multi-tier private cloud storage system using Docker Compose. The system uses Nextcloud as the web application and MariaDB as the database. Instead of deploying each container manually, I used a `docker-compose.yml` file to define and deploy the services together.

## Objectives

* Understand multi-tier application architecture.
* Learn the purpose and structure of a `docker-compose.yml` file.
* Create a Docker Compose configuration using the nano text editor.
* Deploy Nextcloud and MariaDB using Docker Compose.
* Document the deployment process using Markdown.
* Practice Infrastructure as Code (IaC).

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

Through this activity, I learned how to create a Docker Compose configuration and deploy multiple containers at the same time. I also learned how a web application and database can work together using separate containers. I gained more experience with Linux commands, Docker Compose, YAML configuration, and Infrastructure as Code.

