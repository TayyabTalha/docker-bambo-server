Bamboo is a continuous integration and continuous deployment server. Learn more about Bamboo: <https://www.atlassian.com/software/bamboo>


# Overview

This Docker container makes it easy to get an instance of Bamboo up and running.
This is bambo server which can run docker local agent default and you can use it to build docker images

# Quick Start

## Build Images
```
docker build .
```
## Tag Image
```
docker tag <imageId> <repo>
```
## Push Docker Image
```
docker push <repo>
```
## Run Bambo server
```

docker-compose up -d
```
