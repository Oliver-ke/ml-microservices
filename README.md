<include a CircleCI status badge, here>

## Project Overview
ml-microservices is an operational machine learning application that is trained to make housing price prediction. It is supercharged with production ready tools such as
- continuous integration and delivery
- scalable microservice using containers and container orchestration tools (kubernetes)
- develop with infrastructure as code (IaC)

## Running this project
### Local computer
- pull this repository
- create and activate a python virtual environment
- run `make install` to install dependencies
- run `make lint` to link code
- run the app with `python app.py`
- open your terminal and type `./make_prediction.sh` to test

### Docker
- pull this repository
- open your terminal and type `./run_docker.sh`
- open another terminal and type `./make_prediction.sh` to test

### Kubernetes
- pull this repository
- open your terminal and type `./run_kubernetes.sh`
- open another terminal and type `./make_prediction.sh` to test

## Relevant Files
- `app.py` python flask application
- `make_prediction.sh` bash script to test prediction application
- `run_docker.sh` bash script to build image and run with docker
- `run_kubernetes.sh` bash script to run app in a kubernetes cluster