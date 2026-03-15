# Kubernetes DevOps Demo

This project demonstrates deploying a containerized application to Kubernetes using Docker and Minikube.

## Technologies Used

Docker
Kubernetes
Minikube
kubectl
Git

## Project Features

Containerized web application
Kubernetes Deployment
Service exposure using NodePort
Application scaling
Kubernetes self-healing test

## Build Docker Image

docker build -t my-devops-app .

## Deploy to Kubernetes

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## Verify Pods

kubectl get pods

## Access the Application

minikube service nginx-service

## Scaling Example

kubectl scale deployment nginx-deployment --replicas=5

## Self-Healing Test

kubectl delete pod POD_NAME

Kubernetes automatically recreates the deleted pod.