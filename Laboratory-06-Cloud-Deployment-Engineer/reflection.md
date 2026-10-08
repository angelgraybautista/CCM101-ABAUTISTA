# Mission Reflection

This laboratory activity helped me understand how Docker Compose can make cloud deployment easier. Instead of manually typing several Docker commands for every container, I can define the required services in a `docker-compose.yml` file and deploy them together. This makes the deployment process more organized and reduces the possibility of forgetting an important command or configuration.

I also learned that YAML is sensitive to indentation. If I use incorrect spacing or a Tab instead of the proper spaces, the Compose file may not work correctly. This showed me that even a small formatting mistake can cause problems when creating Infrastructure as Code.

We used environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` to provide the database configuration needed by the application. These variables allow the Nextcloud container to know which database, username, and password it should use. I also learned that `MYSQL_HOST=database` allows Nextcloud to find the MariaDB container using its service name.

Deploying Nextcloud made me realize how useful cloud and container technologies can be. It was interesting to see a private cloud storage system become accessible through a browser after only a few deployment steps. Before this activity, I mostly understood cloud computing as using online services and storage. Now, I have a better understanding of how applications can actually be deployed and connected using containers.
