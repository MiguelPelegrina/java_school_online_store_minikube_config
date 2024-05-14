# Kubernetes minikube configuration

This repository is part of my final project for the Java School of T-Systems Iberia and contains the backend. For further information please refer to my documentation at https://miguelpelegrina.github.io/java_school_online_store_documentation/.

## Useful commannds:

### To run a Kubernetes minikube:
- Install Kubernetes on your device: [https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/](https://kubernetes.io/docs/tasks/tools/)

### To run all the applications and servers:
- Set up the docker context as default: ```docker context use default```
- Start the minikube:
  - With default configuration: ```minikube start```
  - With high amount of resources for improved performance: ```minikube start --cpus 8 --memory 16.384```
- ```minikube addons enable ingress```
- ```minikube tunnel```
- Open another terminal: ```minikube dashboard```
- Select __All namespaces__ from the drop-down menu at the top left of the Kubernetes Dashboard to view everything.
  - At the start __default__ is selected and all the related deployments and services related to metrics are in the __monitoring__ namespace.

## Notes:
- The current configuration does not differ between a development and a production environemnt.
- Currently the following services are running:
  - Backend: Java Spring Boot API 
    - API Documentation: OpenAPI (former Swagger)  
  - Frontend: Angular 
  - Database: postgreSQL 
  - DBMS: pgAdmin4 
  - Documentation: Mkdocs
  - Code Analysis: SonarQube
  - Metrics: Prometheus and Grafana  
- I am new to Kubernetes and this is my project to learn how to use it, therefore errors, bad practices, questionable design choices might happen, but improvements will happen over time as it's all part of the learning process!   
