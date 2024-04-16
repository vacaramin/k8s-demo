# k8s-demo

Welcome to the `k8s-demo` repository! This repository contains a variety of Kubernetes samples that demonstrate how to use different types of resources such as ConfigMaps, Services, Deployments, and Secrets. Each example is designed to provide practical insights and best practices for deploying applications on Kubernetes.

## Getting Started

To use these examples, you will need a Kubernetes cluster. You can set one up using [Minikube](https://minikube.sigs.k8s.io/docs/start/) or use any existing Kubernetes environment you have access to.

### Prerequisites

- A Kubernetes cluster
- [kubectl](https://kubernetes.io/docs/tasks/tools/) installed and configured to connect to your cluster

### Repository Structure

This repository is organized as follows:

- ConfigMaps - Examples on how to configure applications using ConfigMaps.
- Services - Demonstrations of various types of services for exposing your applications.
- Deployments - Deployment configurations that showcase different deployment strategies and use cases.
- Secrets - How to securely inject sensitive data into your applications.
Examples
Below are brief descriptions of what you will find in each directory:

#### ConfigMaps

- `simple-configmap.yaml` - Basic example of how to create a ConfigMap.

#### Services

- `simple-service.yaml` - Example of setting up a simple service.

#### Deployments

- `rolling-update-deployment.yaml` - Deployment that demonstrates a rolling update.
Secrets
- `simple-secret.yaml` - Example of how to create and use a Secret.

### Usage

#### To apply an example configuration to your cluster, use the following command

```bash
kubectl apply -f [filename]
```

Replace [filename] with the path to the YAML file you want to apply.
