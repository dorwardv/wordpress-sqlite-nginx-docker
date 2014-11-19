## Wordpress on Nginx using Sqlite instead of MySQL Dockerfile


This repository contains **Dockerfile** of Wordpress on Nginx using Sqlite instead of MySQL


### Base Docker Image

* Nginx Official build for Docker (https://registry.hub.docker.com/_/nginx/)

### Usage

    docker run -d -p 80:80 dorwardv/wordpress-sqlite-nginx-docker

After few seconds, open `http://<host>` to see the wordpress install page.

###Build from Dockerfile
    docker build -t="dorwardv/wordpress-sqlite-nginx-docker" github.com/dorwardv/wordpress-sqlite-nginx-docker
