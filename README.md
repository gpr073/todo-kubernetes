# todo-kubernetes

## Description

A Kubernetes cluster deployed using minikube.
- Three pods are created with the following containers respectively: TodoList, MongoDB, Mongo-Express.
- Deployments was used to create the pods.
- Secrets was used to provide credentials to the database.
- Configmap was used to provide connection string to the application container.
- Service was used to enable the pods to communicate with each other and over the internet.

## Getting Started

### Dependencies

* Minikube

### Executing program

* Download and install minikube.
* Create a secrets file and add in the credentials required.
* Verify minikube is running.
* The web application starts on port 3000.
```
minikube start
kubectl apply -f ./
```
