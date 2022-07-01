# Simple Node

## Overview

This is a very simple, bare-bones NodeJS project created for you to use with Docker and Travis CI for CI/CD.

## Local Setup

- Install dependencies: `npm install`
- Run server: `node server.js`

## Container Setup

- Build image: `docker build .`
- Run container with image: `docker run {image_id}` where `image_id` can be retrieved by running `docker images` and found under the column `IMAGE ID`

## Container teardown

- Remove container: `docker kill {container_id}` where `container_id` can be retrieved by running `docker ps` and found under the column `CONTAINER ID`

## CI / CD Pipeline

- Set up  DOCKER_USERNAME and DOCKER_PASSWORD as environment variable in your Travis account