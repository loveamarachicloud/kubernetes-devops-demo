# Kubernetes Deployment Demo

This project demonstrates deploying a containerized application to Kubernetes using Docker and Minikube.

## Tools Used

Docker
Kubernetes
Minikube
kubectl

## Steps

Build Docker image

docker build -t my-devops-app .

Deploy to Kubernetes

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

Check pods

kubectl get pods

Expose service

minikube service nginx-service

## Features Demonstrated

Container build
Kubernetes deployment
Service exposure
Scaling
Self-healing