# DockerComposeFiles
YAML Files to configure MongoDB and phpMyAdmin/MariaDB with docker-compose command.

## Dependencies
[Git](https://git-scm.com/) and [Docker](https://www.docker.com/) are the dependencies you need to perform these installations.

## Configure root login and password
#### Open the MariaDB.yaml file and configure these values
```
MARIADB_USER=
MARIADB_PASSWORD=
MARIADB_ROOT_PASSWORD=
```
#### Proceed to the same operation with MongoDB.yaml file and configure these values
```
MONGO_INITDB_ROOT_USERNAME: 
MONGO_INITDB_ROOT_PASSWORD: 
```

## Installations
### MariaDB
```sh
git clone https://github.com/ThomasDeOliv/DockerComposeFiles
cd DockerComposeFiles
docker compose -f MariaDB.yaml up
```
### MongoDB
```sh
git clone https://github.com/ThomasDeOliv/DockerComposeFiles
cd DockerComposeFiles
docker compose -f MongoDB.yaml up
```