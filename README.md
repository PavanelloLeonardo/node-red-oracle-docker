# Node-Red Docker with Oracle Drivers

[![Docker Pulls](https://img.shields.io/docker/pulls/pavanello/node-red-oracle.svg)](https://hub.docker.com/r/pavanello/node-red-oracle/)

This image is based on [Node-RED](https://github.com/node-red/node-red-docker) including [node-oracledb](https://github.com/oracle/node-oracledb) and [node-red-contrib-oracledb-mod](https://github.com/vtulluru/node-red-contrib-oracledb-mod) extension.

## Included

* Node-RED 1.3.3
* Node 10
* Alpine Linux
* Oracle Instant Client

## Atention

Use `/usr/lib/instantclient` for path in [node-red-contrib-oracledb-mod](https://github.com/vtulluru/node-red-contrib-oracledb-mod)

## Build

Create a location to store the configuration files:
```bash
git clone https://github.com/PavanelloLeonardo/node-red-oracle-docker.git
cd node-red-oracle-docker
docker build -t **** -f Dockerfile.node-red-oracle-docker .
```
## Run

See [Node-RED](https://hub.docker.com/r/nodered/node-red) documentation

## References

[Node-RED Docker](https://github.com/node-red/node-red-docker)

[Node Red Docker image with Oracle NodeJS Drivers](https://github.com/martindsouza/docker-node-red-oracle)

[Node-Red-Oracle](https://github.com/Tommi2Day/node-red-oracle)

[Docker + Alpine + Instantclient Basic Lite](https://github.com/alfonsoprado/docker-alpine-instantclient-basiclite)

[Node-RED Oracle Database nodes](https://github.com/vtulluru/node-red-contrib-oracledb-mod)


From a little star, because it took work to do :)
Tks!
