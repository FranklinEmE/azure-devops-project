\# 🚀 Azure DevOps End-to-End Project (Flask + Docker + Azure + Kubernetes)



📌 GitHub Repo: https://github.com/FranklinEmE/azure-devops-project.git



\---



\## 📖 Project Overview



This project demonstrates a complete DevOps workflow from application development to cloud deployment and monitoring using Microsoft Azure.



It covers:



\- Flask application development

\- Containerization using Docker

\- Image storage in Azure Container Registry (ACR)

\- Kubernetes deployment on AKS

\- CI/CD pipeline using GitHub Actions

\- Monitoring \& alerting with Prometheus and Grafana



\---



\## 🏗️ Architecture Flow



GitHub → GitHub Actions CI/CD → Docker Build → Azure Container Registry → AKS Deployment → Prometheus \& Grafana Monitoring



\---



\# 📸 Project Screenshots \& Evidence



\---



\## 🔹 1. Azure Resource Group



!\[Resource Group](./screenshots/09-resource-group.png)



\*\*Description:\*\*  

Azure Resource Group containing all infrastructure resources used in the project including AKS, ACR, networking, and monitoring tools.



\---



\## 🔹 2. Azure Container Registry (ACR)



!\[ACR Overview](./screenshots/01-acr-overview.png)



\*\*Description:\*\*  

Azure Container Registry used to securely store Docker images for deployment.



\---



\## 🔹 3. Docker Image Push to ACR



!\[Docker Push](./screenshots/03-docker-push-acr.png)



\*\*Description:\*\*  

Docker image successfully built and pushed to Azure Container Registry.



\---



\## 🔹 4. CI/CD Pipeline Trigger



!\[CI/CD Pipeline](./screenshots/04-github-actions-ci-cd-trigger.png)



\*\*Description:\*\*  

GitHub commit triggered automated CI/CD pipeline using GitHub Actions.



\---



\## 🔹 5. Kubernetes Pod Running



!\[Running Pod](./screenshots/11-k8s-running-pod.png)



\*\*Description:\*\*  

Flask application successfully deployed and running inside Kubernetes (AKS).



\---



\## 🔹 6. Kubernetes Cluster Dashboard



!\[Kubernetes Dashboard](./screenshots/02-k8s-dashboard.png)



\*\*Description:\*\*  

Overview of Kubernetes cluster workloads and health status.



\---



\## 🔹 7. Grafana Monitoring Access



!\[Grafana](./screenshots/05-grafana-access.png)



\*\*Description:\*\*  

Grafana dashboard used for system monitoring and visualization of cluster metrics.



\---



\## 🔹 8. CPU Usage Alert



!\[CPU Alert](./screenshots/06-cpu-alert.png)



\*\*Description:\*\*  

Automated alert triggered when CPU usage exceeds defined threshold.



\---



\## 🔹 9. Memory Usage Alert



!\[Memory Alert](./screenshots/07-memory-alert.png)



\*\*Description:\*\*  

Memory monitoring system detecting high resource usage in the cluster.



\---



\## 🔹 10. Pod Health Alert



!\[Pod Health](./screenshots/08-pod-health-alert.png)



\*\*Description:\*\*  

Kubernetes health monitoring ensuring application availability and stability.



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

├── 04-github-actions-ci-cd-trigger.png

├── 05-grafana-access.png

├── 06-cpu-alert.png

├── 07-memory-alert.png

├── 08-pod-health-alert.png

├── 09-resource-group.png

├── 11-k8s-running-pod.png





\---



\# 🔐 Key Features



\- Flask web application

\- Docker containerization

\- Azure Container Registry (ACR)

\- Kubernetes deployment on AKS

\- CI/CD automation using GitHub Actions

\- Monitoring using Prometheus \& Grafana

\- Real-world DevOps workflow



\---



\# 📊 What I Learned



\- Docker image building and containerization

\- Azure cloud infrastructure (ACR, AKS)

\- Kubernetes deployment and scaling

\- CI/CD pipeline automation

\- Monitoring and observability (Prometheus \& Grafana)

\- End-to-end DevOps workflow implementation



\---



\# 🚀 Future Improvements



\- Full production-grade AKS setup

\- Auto-scaling and load balancing

\- Terraform full Infrastructure as Code (IaC)

\- Multi-environment deployment (dev/staging/prod)

\- Advanced alerting and logging (Loki / ELK stack)



\---



\# 👨‍💻 Author



Franklin Chidera Emmanuel  

GitHub: https://github.com/FranklinEmE



\---



\# ⭐ Final Note



This project demonstrates a complete DevOps pipeline from code to cloud deployment using industry-standard tools and Azure cloud services.

