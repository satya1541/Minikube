# Minikube and Kubernetes 

## Kubernetes
An open-source container orchestration platform for automating the deployment, scaling, and management of containerized applications.

## Minikube
A tool that makes it easy to run Kubernetes locally. It creates a single-node Kubernetes cluster on your machine.

## Pod
The smallest deployable unit in Kubernetes, representing a single instance of a running process in a cluster.

## Node
A worker machine in Kubernetes, which can be either a physical or virtual machine. Nodes run pods and are managed by the control plane.

## Deployment
A Kubernetes resource that provides declarative updates to applications. It manages the creation and scaling of a set of pods.

## Service
An abstraction that defines a logical set of pods and a policy by which to access them. Services enable communication between different components in a cluster.

## Kubectl
A command-line tool for interacting with Kubernetes clusters. It allows users to create, inspect, update, and delete Kubernetes resources.

## Namespace
A way to divide cluster resources between multiple users. Namespaces help in organizing resources and providing scope for names.

## Ingress
An API object that manages external access to services, typically HTTP. It provides load balancing, SSL termination, and name-based virtual hosting.

## ConfigMap
A Kubernetes object that allows you to decouple configuration artifacts from image content to keep your containerized applications portable.

## Secret
A Kubernetes object that stores sensitive data, such as passwords, OAuth tokens, and ssh keys. Secrets are base64-encoded for security.

## Volume
A directory that contains data, accessible to containers in a pod. Volumes persist data across container restarts.

## Helm
A package manager for Kubernetes, which helps in managing Kubernetes applications using Helm charts.

## Kubelet
An agent that runs on each node in the cluster. It ensures that containers are running in a pod by monitoring their health and status.

## Control Plane
The component of Kubernetes responsible for managing the cluster. It makes decisions about the cluster (e.g., scheduling) and detects and responds to cluster events.

---

