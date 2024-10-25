## Steps

* After writing the dockerfile & docker-composer.yml file just run the "docker compose build" command
* then run "docker-compose up"

## Run docker compose in background. 
docker-compose up -d

## Go to Docker Terminal
Syntax: docker exec -it <folder_name> bash
EG: docker exec -it laravel-docker bash

# Docker Cheatsheet
https://docs.docker.com/get-started/docker_cheatsheet.pdf


## Laravel ##

# create new project in with Latest Laravel
composer create-project laravel/laravel <example-app-name>

## Create any specific version of laravel
composer create-project laravel/laravel:^10.0 example-app

# Start Local Dev server
php artisan serve
php artisan serve --host=localhost --port=9002


# Refrence
https://youtu.be/V-MDfE1I6u0
https://github.com/pitocms/laravel-docker