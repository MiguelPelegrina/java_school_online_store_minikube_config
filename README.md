# Kubernetes minikube configuration
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
## WIP Current version requires installing Prometheus and Grafana on the host machine, working on implementing Infrastructure as Code properly
### To run Prometheus
- Install prometheus:
- 
### To run Grafana
- Install Grafana:
- 

Notes:
I am new to Kubernetes and this is my project to learn how to use it, therefore errors, bad practices, questionable design choices might happen, but improvements will happen over time as it's all part of the learning process!   
