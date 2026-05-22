# azure-devops-project

Azure DevOps learning project with Docker, Kubernetes and Azure CLI



\# 🚀 Azure DevOps End-to-End Project (Flask + Docker + Azure + Kubernetes)



📌 GitHub Repo: https://github.com/FranklinEmE/azure-devops-project.git



\---



\## 📖 Project Overview



This project demonstrates a complete DevOps workflow from application development to cloud deployment and monitoring using Microsoft Azure.



It covers:

\- Application development (Flask)

\- Containerization with Docker

\- Image storage in Azure Container Registry (ACR)

\- Kubernetes deployment (AKS concept)

\- Monitoring \& alerting system

\- CI/CD workflow simulation



\---



\## 🏗️ Architecture Flow



Flask App → Docker Image → Azure Container Registry → Kubernetes Deployment → Monitoring \& Alerts



\---



\# 📸 Project Screenshots \& Explanation



\---



\## 🔹 1. Azure Resource Group

!\[Resource Group](screenshots/09-resource-group.png)



\*\*Description:\*\*  

This is the Azure Resource Group that contains all cloud resources used in the project. It acts as a logical container for managing infrastructure.



\---



\## 🔹 2. Azure Container Registry (ACR)

!\[ACR](screenshots/01-acr-overview.png)



\*\*Description:\*\*  

Private Docker registry used to store and manage container images securely in Azure.



\---



\## 🔹 3. Docker Image Push to ACR

!\[Docker Push](screenshots/03-docker-push-acr.png)



\*\*Description:\*\*  

The Docker image was successfully built and pushed to Azure Container Registry.



\---



\## 🔹 4. CI/CD Pipeline Trigger

!\[CI/CD](screenshots/04-cicd-trigger.png)



\*\*Description:\*\*  

A Git commit triggered the CI/CD pipeline demonstrating automated delivery workflow.



\---



\## 🔹 5. Kubernetes Dashboard

!\[Kubernetes](screenshots/02-k8s-dashboard.png)



\*\*Description:\*\*  

Shows Kubernetes cluster status including running workloads and system health.



\---



\## 🔹 6. Running Container Image

!\[Container Running](screenshots/10-acr-running-image.png)



\*\*Description:\*\*  

The containerized application is successfully running from the Azure registry image.



\---



\## 🔹 7. Running Kubernetes Pod

!\[Pod Running](screenshots/11-k8s-running-pod.png)



\*\*Description:\*\*  

The application is deployed successfully as a running Kubernetes pod.



\---



\## 🔹 8. Grafana Monitoring Access

!\[Grafana](screenshots/05-grafana-access.png)



\*\*Description:\*\*  

Monitoring dashboard used to observe system metrics and cluster performance.



\---



\## 🔹 9. CPU Usage Alert

!\[CPU Alert](screenshots/06-cpu-alert.png)



\*\*Description:\*\*  

Automated alert triggered when CPU usage exceeds threshold limits.



\---



\## 🔹 10. Memory Usage Alert

!\[Memory Alert](screenshots/07-memory-alert.png)



\*\*Description:\*\*  

Memory monitoring system detects and alerts high resource consumption.



\---



\## 🔹 11. Pod Health Alert

!\[Pod Health](screenshots/08-pod-health-alert.png)



\*\*Description:\*\*  

Kubernetes health monitoring ensures pod reliability and uptime.



\---



\# 📂 Project Structure



azure-devops-app/

│

├── app.py

├── Dockerfile

├── deployment.yaml

├── service.yaml

├── requirements.txt

├── README.md

│

├── terraform/ (optional)

│

└── screenshots/

├── 01-acr-overview.png

├── 02-k8s-dashboard.png

├── 03-docker-push-acr.png

├── 04-cicd-trigger.png

├── 05-grafana-access.png

├── 06-cpu-alert.png

├── 07-memory-alert.png

├── 08-pod-health-alert.png

├── 09-resource-group.png

├── 10-acr-running-image.png

├── 11-k8s-running-pod.png





\---



\# 🔐 Key Features



\- Flask web application

\- Docker containerization

\- Azure Container Registry (ACR)

\- Kubernetes deployment concepts

\- CI/CD workflow simulation

\- Monitoring \& alerting system

\- Cloud infrastructure on Microsoft Azure



\---



\# 📊 What I Learned



\- Containerization with Docker

\- Azure cloud infrastructure

\- Kubernetes basics

\- CI/CD pipelines

\- Monitoring and observability

\- End-to-end DevOps workflow



\---



\# 🚀 Future Improvements



\- Full CI/CD with GitHub Actions

\- Production AKS cluster deployment

\- Auto-scaling and load balancing

\- Prometheus + Grafana integration

\- Multi-environment deployment (dev/staging/prod)



\---



\# 👨‍💻 Author



Franklin Chidera Emmanuel  

GitHub: https://github.com/FranklinEmE



\---



\# ⭐ Final Note



This project demonstrates a real-world DevOps pipeline from code to cloud deployment using industry-standard tools.

