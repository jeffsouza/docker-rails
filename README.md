## Description

Dockerize a Rails application

## What it includes?

- Docker Images

   - [jeffdesouza/rails-proxy (latest)](https://github.com/jeffsouza/docker-rails-proxy)
    
- Services

   - PostgreSQL (9.4.1)
   - pgAdmin4 (3+)

## Setup

```bash
$ git clone git@github.com:jeffsouza/docker-rails.git
$ cd docker-rails
$ mkdir rails-app
$ cp YOUR_APPLICATION_FOLDER_PATH rails-app
```

## Run

```bash
$ docker-compose build
$ docker-compose up -d
```

## Use

- Application - http://localhost
- pgAdmin - http://localhost:5050

## PostgreSQL Access

> Host: db<br/>
> Port: 5432<br/>
> Username: postgres<br/>
> Password: 123