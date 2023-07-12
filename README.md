[![CircleCI](https://dl.circleci.com/status-badge/img/gh/tintd2/project-ml-microservice-kubernetes/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/tintd2/project-ml-microservice-kubernetes/tree/main)
# project-ml-microservice-kubernetes
The K8s sample project python machine learning vs flask webserver.

1.Run Docker 

  - Run on docker `./run_docker.sh`
  
  - Call api `./make_prediction.sh`


2.Run Kubernetes

 - Run on docker `./run_docker.sh`
 - Upload image to docker hub `./upload_docker.sh`
 - Run on k8s `./run_kuberneter.sh`
 - Call Api `./make_prediction.sh`


Prequiment: Docker Hub, Docker Desktop enable kubernetes.

- app.py main source.
- requirements.txt library dependences.
- Dockerfile for create docker images can run container.
- run_docker.sh script build docker image using Dockerfile
- upload_docker.sh script upload docker images to docker hub
- run_docker.sh create container.
- run_kuberneter.sh run source using kubenetes on local.
- output_txt_files: log folder
- model_data: app asssets
