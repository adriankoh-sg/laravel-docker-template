# Laravel Web Project with Docker
This is a project template setup using Laravel with docker.

## Specifications
Docker images use:
- PHP 8.5 with Apache web server
- MySQL 8.4
- phpMyAdmin 5.3

## Local Setup
You need to install the following on your local machine.
- PHP 8.5.3 (For MacOS, can use brew)
- Composer
- NodeJS
- Docker

## Project setup
- Install dependency: 
> ```composer install```   
> ```npm install```   
> ```npm run build```   

- Start docker and setup db
> ```docker compose up -d```   
> ```php artisan migrate```   

- To stop the docker:
> ```docker compose down```   


## Start project
Use the following command to start the project.   
```docker compose up```

Open browser: `http://localhost:8080`

> phpMyAdmin: `http://localhost:8001`
