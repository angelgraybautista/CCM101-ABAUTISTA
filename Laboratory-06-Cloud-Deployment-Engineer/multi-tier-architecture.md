# Multi-Tier Architecture

## What is Two-Tier Architecture?

A two-tier architecture separates an application into two main parts: the web/application tier and the database tier. In this activity, Nextcloud serves as the application while MariaDB works as the database.

## The Web/Application Tier

The web/application tier is responsible for providing the user interface and handling HTTP requests. In this activity, the Nextcloud container acts as the application tier. Users access Nextcloud through a web browser.

## The Database Tier

The database tier is responsible for storing persistent information used by the application. MariaDB is used as the database in this activity. It stores information such as user accounts and Nextcloud data.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container has its own role, so problems or changes in one service can be handled separately without putting everything into one container.

