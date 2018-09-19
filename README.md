Bamboo is a continuous integration and continuous deployment server. Learn more about Bamboo: <https://www.atlassian.com/software/bamboo>


# Overview

This Docker container makes it easy to get an instance of Bamboo up and running.
This is bambo server which can run docker local agent default and you can use it to build docker images

# Quick Start

``
docker build .
docker tag <imageId> <repo>
docker push <repo>
docker-compose up -d
``
