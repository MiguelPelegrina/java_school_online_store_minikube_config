# Java School Online store minikube configuration
## Useful commannds:
### To run a Kubernetes minikube:
- 
### To run all the applications and servers:
- Set up the docker context as default: ```docker context use default```
- Start the minikube:
  - With default configuration: ```minikube start```
  - With high amount of resources for improved performance: ```minikube start --cpus 8 --memory 16.384```
- ```minikube addons enable ingress```
- Open a new terminal: ```minikube tunnel```
- Open another terminal: ```minikube dashboard```
## WIP Current version requires installing Prometheus and Grafana on the host machine, working on implementing Infrastructure as Code properly
### To run Prometheus
- Install prometheus:
- 
### To run Grafana
- Install Grafana:
- 
