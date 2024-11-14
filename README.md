# WordPress with MySQL and Nginx using Docker
Docker setup for Laravel with Nginx and MySQL. Quickly spin up a Laravel environment with optimized configurations for PHP and Nginx. 

## Prerequisites

- Docker
- Docker Compose

## Setup Guide

**Clone the Repository**
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

Once the containers are running, you can access the WordPress site at **http://localhost:8080**