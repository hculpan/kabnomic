# Building KabNomic

By default, the KabNomic webservice listens on port 8080 to service requests.

## Docker
This project may be built inside a Docker container.

The build the docker image:  
`docker build -t kabnomic .`

To run:  
`docker run -p 8080:8080 -it kabnomic`

