# Kubernetes DevOps Demo

Dockerized web application deployed on Kubernetes using Minikube.  
This project demonstrates container builds, Kubernetes deployments, service exposure, scaling, and self-healing behavior.
## Architecture

![Architecture](screenshots/architecture.png)
## Technology Stack

- Docker
- Kubernetes
- Minikube
- kubectl
- Git
- Visual Studio Code
## Quick Start

1 Start Minikube
minikube start
2 Build Docker Image
docker build -f docker/Dockerfile -t my-devops-app .
3 Deploy to Kubernetes
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
4 Verify the Pods
kubectl get pods
5 Access the Application
minikube service nginx-service

