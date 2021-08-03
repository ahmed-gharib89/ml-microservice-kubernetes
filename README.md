[![CircleCI](https://circleci.com/gh/ahmed-gharib89/ml-microservice-kubernetes/tree/main.svg?style=svg)](https://circleci.com/gh/ahmed-gharib89/ml-microservice-kubernetes/tree/main)

## Project Overview

The purpose of this project is to operationalize a Python flask app that serves out predictions (inference) about housing prices through API calls. and deploy it on a kubernetes cluster.

## Setup the Environment

- Create a virtualenv and activate it
- Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone: `python app.py`
2. Run in Docker: `./run_docker.sh`
3. Run in Kubernetes: `./run_kubernetes.sh`

### Kubernetes Steps

- Setup and Configure Docker locally
- Setup and Configure Kubernetes locally
- Create Flask app in Container
- Run via kubectl
