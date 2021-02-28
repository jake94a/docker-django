# django project utilizing docker

###### adapated from

[Quickstart: Compose and Django](https://docs.docker.com/compose/django/)

## This is a practice project

- define a Dockerfile using python3
- define a requirements.txt file using Django
- create a docker-compose.yml
  - two services: web & db (postgres)

## Setup

- initialize django project in Docker by running `sudo docker-compose run web django-admin startproject example_project .`
  - this runs the web service image
  - then run the django project initializing command using the `web` service
