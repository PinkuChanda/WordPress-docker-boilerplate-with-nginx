# WordPress Docker Environment with Nginx and MySQL

This Docker configuration sets up a WordPress environment using Nginx as a web server and MySQL as the database backend. The setup allows for quick deployment of WordPress with optimal configurations for development.


## Prerequisites

- Docker
- Docker Compose

## Setup Guide

**Clone the Repository**

To get started, clone the repository and navigate into the project directory:

   ```
   git clone <repo-url>
   cd <repo-directory>
   ```

**Start the Docker Containers**

To start all services, run:

```
docker compose up -d --build
```   

**Access WordPress:**

Once started, you can access the services as follows:

**Nginx (WordPress site):** http://localhost:8080

**MySQL Database:** Accessible on port 3306 by MySQL clients.