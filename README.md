# Mariadb
## Configuration
user: `root`

password: `example`

host(for tcp agent): `localhost`

host (for adminer): `db`

port: `3306`

present table `example`

## Sart

`docker-compose up -d` -- like service

`docker-compose up` -- with logs

Connect to db use terminal `docker exec -ti mariadb bash`

Where mariadb - container name.
