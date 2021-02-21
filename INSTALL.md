# Installation

## Nginx

This application uses nginx as a reverse proxy.  To setup, install as a server on the host machine.  Use the `app.conf` in the `nginx-conf` directory to configure the server.  Note that this is with Let's Encypt ceritificates installed, so that should be done as well.

## Go application
The web app will be built and deployed using `docker compose`.  The configuration for this is in `Dockerfile` and `docker-compose.ymal`.

## MySql
This application uses mysql for the data store.  It should also run inside of a docker container (see the `docker-compose.yaml`, but it should use a Docker volume so that the data itself will be stored outside of the container. 
