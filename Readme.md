# Docker Mongodb Build

The following repo contains a MongoDB docker-compose.yml.

## Requirements
  1) Docker
  2) Docker-compose

## Setup
  Modify the docker-compose username and password:
  ```
    MONGO_INITDB_ROOT_USERNAME=user
    MONGO_INITDB_ROOT_PASSWORD=password
  ```

## Build & Run
  Run
  ```
    docker-compose up 
  ```

  Run Detached
  ``` 
    docker-compose up -d
  ```
