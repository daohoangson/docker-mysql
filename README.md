# Docker MySQL
Quickly start a MySQL docker container that persist data on the host machine.

## Requirements
* [Docker](https://docs.docker.com/installation/)
* [Docker Compose](https://docs.docker.com/compose/install/)

## Usage
 * `git clone git@github.com:daohoangson/docker-mysql.git`
 * `cd docker-mysql`
 * `docker-compose up -d`

## Connect to MySQL Server
You can connect to MySQL with any client at port 13306 of the docker machine. Root password is "password".
Another option is to use the included `client` container: `docker-compose run client`
