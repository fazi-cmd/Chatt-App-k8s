# ChatApp Kubernetes Deployment 🚀

This repository contains the **Kubernetes (K8s) configuration** for the ChatApp project.

I created this repository as part of my journey to learn Kubernetes and practice deploying a real full-stack application using Kubernetes concepts.

The original ChatApp project was taken from **Afzal's repository**, and I would like to give credit and thanks to him for providing the original project that I used for learning and Kubernetes implementation.

## 🎯 Purpose

The main purpose of this repository is to take an existing full-stack application and apply the Kubernetes concepts I have learned.

I am currently focusing on **Kubernetes and container orchestration**, so this repository mainly contains the Kubernetes configuration and deployment files rather than the complete application source code.

## ☸️ Kubernetes Concepts I Learned & Applied

During this project, I studied and practiced several important Kubernetes concepts, including:

* 🟢 Pods
* 🟢 Deployments
* 🟢 ReplicaSets
* 🟢 Services
* 🟢 ClusterIP
* 🟢 NodePort
* 🟢 Ingress
* 🟢 ConfigMaps
* 🟢 Secrets
* 🟢 Persistent Volumes (PV)
* 🟢 Persistent Volume Claims (PVC)
* 🟢 Namespaces
* 🟢 Labels & Selectors
* 🟢 Service Discovery
* 🟢 Kubernetes Networking
* 🟢 Ingress Controllers
* 🟢 Helm
* 🟢 Service Mesh
* 🟢 Kubernetes Cluster Architecture
* 🟢 Scheduling & Nodes
* 🟢 Scaling & Replicas
* 🟢 Kubernetes YAML configuration
* 🟢 Debugging Pods and Containers
* 🟢 Port Forwarding

## 🏗️ Application Architecture

The application consists of:

```text
                 User
                   │
                   ▼
              Kubernetes
                Ingress
                   │
                   ▼
              Frontend
                   │
                   ▼
               Backend
                   │
                   ▼
               MongoDB
```

The frontend, backend, and database run as Kubernetes workloads, while Kubernetes Services provide internal communication between the application components.

## 📂 Repository Structure

```text
k8s/
│
├── README.md
├── backend-deployment.yml
├── frontend-deployment.yml
├── ...
```

Additional Kubernetes configuration files can be added as the project continues to evolve.

## 🧪 Learning Through Practice

This project is not only about deploying an application. It is primarily a **hands-on Kubernetes learning project**.

While working on it, I practiced concepts such as:

* Creating and managing Pods
* Creating Deployments
* Exposing applications using Services
* Internal service-to-service communication
* Managing application configuration
* Managing sensitive information using Secrets
* Persistent storage
* Routing traffic using Ingress
* Working with Kubernetes namespaces
* Debugging failed containers and Pods
* Using `kubectl`
* Port forwarding
* Understanding Kubernetes networking
* Exploring Helm
* Understanding Service Mesh architecture

## 🙏 Credits

Special thanks to **Afzal** for the original ChatApp project that I used as the foundation for this Kubernetes learning project.

Original project:

**Full-Stack ChatApp by Afzal**

I used the original application to focus on learning, implementing, and experimenting with Kubernetes.

## 🚀 What's Next?

This repository represents my current Kubernetes learning stage.

I plan to continue improving this project by exploring and implementing more advanced DevOps and cloud-native technologies, including:

* Advanced Kubernetes networking
* Helm deployments
* Service Mesh
* Monitoring with Prometheus & Grafana
* GitHub Actions CI/CD
* Argo CD
* Terraform
* Kubernetes on AWS
* Production-grade deployments

---

### 📚 Learning by Building

> **Learn → Build → Break → Debug → Improve → Repeat**

This project is part of my journey toward becoming a **DevOps / Cloud Engineer**.

<img width="1872" height="935" alt="Screenshot from 2026-09-08 21-02-44" src="https://github.com/user-attachments/assets/45824583-a7c9-478a-95c9-d69c8d4b89a9" />



<img width="1920" height="1080" alt="Screenshot from 2026-09-09 11-23-55" src="https://github.com/user-attachments/assets/68b775b5-d5c9-4254-8bc9-f6d99bf58a5b" />


<img width="1915" height="986" alt="Screenshot from 2026-09-09 11-38-19" src="https://github.com/user-attachments/assets/6eb40f34-b353-4d4d-a53f-14f95a8cef25" />




<img width="1915" height="986" alt="Screenshot from 2026-09-09 11-39-16" src="https://github.com/user-attachments/assets/29aa63f0-aa00-4257-8ec4-3e0e04d2f115" />

