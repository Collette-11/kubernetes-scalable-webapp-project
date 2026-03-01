\# Kubernetes Scalable Web Application Deployment (Local Multi-Cloud Simulation)



\## 📌 Project Overview



This project demonstrates the deployment of a containerized web application using Kubernetes in a local cloud-simulated environment powered by Minikube and Docker.



The objective was to simulate real-world cloud-native deployment practices such as container orchestration, horizontal scaling, automated self-healing, and Infrastructure-as-Code without relying on paid public cloud platforms.



---



\## 🛠️ Technologies Used



\* Kubernetes (Minikube)

\* Docker

\* kubectl CLI

\* Nginx Web Server

\* YAML (Infrastructure-as-Code)



---



\## 🚀 Deployment Steps



1\. Deployed an Nginx containerized web application using Kubernetes.

2\. Exposed the application externally using a NodePort service.

3\. Scaled application replicas from 1 to 3 to simulate horizontal scaling.

4\. Simulated application failure by deleting a running pod.

5\. Observed Kubernetes self-healing by automatic pod recreation.

6\. Exported deployment and service configuration files as YAML for version-controlled Infrastructure-as-Code.



---



\## 📈 Key Features Demonstrated



\* Containerized Application Deployment

\* Horizontal Pod Scaling

\* ReplicaSet Management

\* Self-Healing Infrastructure

\* Fault Tolerance Simulation

\* Service Exposure using NodePort

\* Infrastructure-as-Code (IaC)



---



\## 📂 Project Structure



kubernetes-scalable-webapp-project/

┣ hello-app-deployment.yaml

┣ hello-app-service.yaml

┗ README.md



---



\## 🎯 Outcome



Successfully simulated cloud-native deployment and scaling of a web application using Kubernetes in a local environment, demonstrating DevOps best practices applicable to multi-cloud platforms.



