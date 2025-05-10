# Kubernetes Intro

- Its an open-source system that helps:
    - Deploy containerised apps
    - Scale them up or down
    - Heal them if they crash
    - Manage how they talk to each other

Core Kubernetes concepts:
- Clusters: A group of machines in Kubernetes
- Node: A machine in a cluster (virtual or real)
- Pod: One or more containers
- Deployment: Instructions for running and updating the pods
- Service: The way users reach the app


### Pod
- Smallest unit in Kubernetes.
- A pod can have 1 or more containers.
- All containers in a pod share the same network.

### Node
- Could be a real or a VM.
- Kubernetes runs your pods in the node.
- Nodes are managed by control plane. 

### Deployment
- Defines how many replicas of your app to run. 
- Allows zero-downtime updates and automatic healing.

### Service
- Makes your app accessible.
- Provides a stable endpoint even if Pod IPs keep changing. 

### Control Plane
- The "brains" of Kubernetes. Schedules Pods, tracks their health, makes decisions. 