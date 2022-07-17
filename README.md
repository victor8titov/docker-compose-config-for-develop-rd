# Config for working with postgresql, pgAdmin, redis

## Description

A simple docker compose config for working the PostgreSQL database, pgAdmin control panel, and Redis database.

## Install

Before using the commands, go to the config directory. And create **.env** file where indicate the parameters to start the database. As an example, there is a file **.env.example** to understand what variables must be indicated.

*After created .env file you can start to build config*

build config

```cli
docker compose build
```

start working

```cli
docker compose up -d
```

stop working

```cli
docker compose down 
```
