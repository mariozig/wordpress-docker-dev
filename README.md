# wordpress-docker-dev

A docker-compose.yml for doing **local** wordpress development using official images.

## What's Happening Here?

For me, Docker is the fastest way to setup Wordpress and get to work.  This repo provides a `docker-compose.yml` that will stand up the following: 

- A WordPress installation [[link](https://hub.docker.com/_/wordpress/)]
- Maria DB [[link](https://hub.docker.com/_/mariadb/)]
- phpMyAdmin [[link](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)]

On first run the Wordpress source will be setup locally and WP's config.php will be updated/ready to go -- all thanks to the official wordpress Docker image.

## Usage

- Copy the `docker-compose.yml` from this repo
- `docker-compose up`
- WordPress: [http://localhost:8080](http://localhost:8080)
- phpMyAdmin: [http://localhost:8181](http://localhost:8181)
 - login: root
 - password: password
