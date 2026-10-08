# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the different containers that will be used by the application. In this project, there are two services: `database` and `app`.

The `database` service uses the MariaDB image, while the `app` service uses the Nextcloud image.

## How Does Nextcloud Find the Database?

Nextcloud finds the MariaDB database using the `MYSQL_HOST` environment variable:

```yaml
MYSQL_HOST=database
```

The value `database` refers to the name of the database service in the Docker Compose file. This allows the Nextcloud container to communicate with the MariaDB container.

## Docker Run vs Docker Compose

The `docker run` command is normally used to create and start an individual container. Docker Compose is useful when an application requires multiple containers.

In this activity, I used:

```bash
docker-compose up -d
```

This command starts the services defined in the `docker-compose.yml` file together. This makes deploying a multi-container application easier than manually starting each container.

## Environment Variables

The Compose file uses environment variables such as:

```yaml
MYSQL_PASSWORD=cloudnova_pass
MYSQL_DATABASE=nextcloud_db
MYSQL_USER=nextcloud_user
MYSQL_HOST=database
```

These variables provide the database connection information that Nextcloud needs to communicate with MariaDB.

