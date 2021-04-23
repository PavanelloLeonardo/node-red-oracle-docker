# Node-Red Docker with Oracle Drivers

[! [Docker Pulls] (https://img.shields.io/docker/pulls/tommi2day/node-red-oracle.svg)] (https://hub.docker.com/r/tommi2day/node-red -oracle /)
This image is based on [Node-RED] (https://github.com/node-red/node-red-docker) including [node-oracledb] (https://github.com/oracle/node-oracledb) and [node-red-contrib-oracledb-mod] (https://github.com/vtulluru/node-red-contrib-oracledb-mod) extension.

## Included

* Node-RED 1.3.3
* Node 10
* Alpine Linux
* Oracle Instant Client

## Atention

Use '/usr/lib/instantclient' for path in [node-red-contrib-oracledb-mod] (https://github.com/vtulluru/node-red-contrib-oracledb-mod)

## Build

Create a location to store the configuration files:
``
git clone https://github.com/Tommi2Day/node-red-oracle.git
cd node-red-oracle
docker build -t tommi2day / node-red-oracle --build-arg ORACLE_VERS = 12.1.0.2.0 -f Dockerfile.node-red-oracle.
``
## Run

See [Node-RED] documentation (https://hub.docker.com/r/nodered/node-red)

## References

[Node-RED Docker] (https://github.com/node-red/node-red-docker)
[Node Red Docker image with Oracle NodeJS Drivers] (https://github.com/martindsouza/docker-node-red-oracle)
[Node-Red-Oracle] (https://github.com/Tommi2Day/node-red-oracle)
[Docker + Alpine + Instantclient Basic Lite] (https://github.com/alfonsoprado/docker-alpine-instantclient-basiclite)
[Node-RED Oracle Database nodes] (https://github.com/vtulluru/node-red-contrib-oracledb-mod)


From a little star, because it took work to do :)
Tks!