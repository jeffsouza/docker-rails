## Description

Dockerize a Rails application

## What it includes?

- Docker Images

   - [jeffdesouza/rails-proxy (latest)](https://github.com/jeffsouza/docker-rails-proxy)
   - [jeffdesouza/rails-prepare (latest)](https://github.com/jeffsouza/docker-rails-prepare)
    
- Services

   - PostgreSQL (9.4.1)
   - pgAdmin4 (3+)

## Configuration

1. Copy the application folder and paste inside the docker-rails folder

2. In file docker-compose.yml change "./rails-app" to the path of the folder you just pasted

## Run

```bash
$ docker-compose up -d
```

## Use

- Application - http://localhost

- pgAdmin - http://localhost:8080

## PostgreSQL Access

> Host: db<br/>
> Port: 5432<br/>
> Username: postgres<br/>
> Password: 123