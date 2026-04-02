# ☸️ Kubernetes Learning

![Container Orchestration](https://img.shields.io/badge/Technology-Kubernetes-blue)
![Platform](https://img.shields.io/badge/Platform-K8s-326CE5)
![CLI](https://img.shields.io/badge/CLI-kubectl-326CE5)
![Containers](https://img.shields.io/badge/Containers-Docker-2496ED)
![Editor](https://img.shields.io/badge/Editor-VS%20Code-007ACC)
![Version Control](https://img.shields.io/badge/Version%20Control-Git-orange)
![Repository](https://img.shields.io/badge/Repository-GitHub-black)

This folder contains my hands-on learning and practice related to Kubernetes.

The purpose of this section is to document Kubernetes concepts, architecture, and practical tasks performed during my DevOps learning journey.

---

## Topics Covered

- Kubernetes Fundamentals  
- Cluster Architecture  
- Nodes and Pods  
- Deployments  
- ReplicaSets  
- Services  
- Namespaces  
- ConfigMaps & Secrets  
- Scaling Applications  
- Rolling Updates & Rollbacks  

---

## Tools Used

- Kubernetes (K8s)  
- kubectl CLI  
- Docker  
- Visual Studio Code  
- Git  
- GitHub  

---

## Practice Tasks

This folder includes various practical tasks performed using Kubernetes such as:

- Creating and managing Pods  
- Deploying applications using Deployments  
- Scaling applications using ReplicaSets  
- Exposing applications using Services  
- Managing configurations using ConfigMaps  
- Performing rolling updates and rollbacks  
- Debugging cluster and application issues  

---

## Architecture Overview

Kubernetes follows a master-worker architecture:

- Control Plane (Master Node)
  - API Server
  - Scheduler
  - Controller Manager
  - etcd

- Worker Nodes
  - Kubelet
  - Kube Proxy
  - Container Runtime (Docker)
