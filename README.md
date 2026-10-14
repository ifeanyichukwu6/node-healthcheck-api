![CI Pipeline](https://github.com/ifeanyichukwu6/node-healthcheck-api/actions/workflows/ci.yml/badge.svg)

# node-healthcheck-api
A containerized Node.js REST API with a GitHub Actions pipeline that builds the Docker image on every push

## Features
- **Node.js & Express API**: Exposes a `/health` endpoint returning JSON health status.
- **Dockerized**: Containerized application using multi-stage lightweight Alpine base image.
- **CI/CD Pipeline**: Automated build and test workflow powered by GitHub Actions.