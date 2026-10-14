![CI Pipeline](https://github.com/ifeanyichukwu6/node-healthcheck-api/actions/workflows/ci.yml/badge.svg)

# node-healthcheck-api
A containerized Node.js REST API with a GitHub Actions pipeline that builds the Docker image on every push

## Features
- **Node.js & Express API**: Exposes a `/health` endpoint returning JSON health status.
- **Dockerized**: Containerized with a Dockerfile using a lightweight Node Alpine base image.
- **CI Pipeline**: A GitHub Actions workflow installs dependencies and builds the Docker image on every push to main.