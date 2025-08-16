# 🚀 3-Tier DevSecOps Mega Project
<p align="center">
  <img src="https://img.shields.io/badge/Architecture-3--Tier-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DevSecOps-CI%2FCD-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-React-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-Node.js-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Orchestration-Kubernetes-purple?style=for-the-badge" />
</p>

## 📑 Table of Contents
- [📖 Introduction](#-introduction)
- [🏗️ Architecture](#️-architecture)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Project Structure](#-project-structure)
- [⚡ Quick Start](#-quick-start)
- [🐳 Run with Docker](#-run-with-docker)
- [🔄 CI/CD with Jenkins](#-cicd-with-jenkins)
- [☸️ Kubernetes & EKS](#️-kubernetes--eks)
- [🚧 Future Improvements](#-future-improvements)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

## 📖 Introduction
This repository showcases a **3-Tier Application** built and deployed using **DevSecOps best practices**.  
It demonstrates:
- **Frontend (React)**  
- **Backend API (Node.js / Express)**  
- **Database Layer**  
Integrated with **CI/CD pipelines**, **Slack notifications**, **Docker**, and **Kubernetes (EKS)** for production-grade deployment.  

## 🏗️ Architecture
The project follows a **3-Tier Architecture**:
```
[ Client (React) ]  <-->  [ API (Node.js / Express) ]  <-->  [ Database Layer ]
```
> 🔒 Security & automation are enforced with **DevSecOps pipelines**.

## ✨ Features
✅ Modern **3-Tier application** (Frontend + API + Database)  
✅ **CI/CD with Jenkins** (automated build, test & deploy)  
✅ **Slack Notifications** for build pipeline updates  
✅ **Dockerized services** with `docker-compose.yaml`  
✅ **Kubernetes deployment manifests** for EKS  
✅ **Scalable architecture** suitable for production  
✅ **Cloud-ready** setup for AWS  

## 🛠️ Tech Stack
- **Frontend:** React, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** (Add DB used, e.g. MongoDB / PostgreSQL)  
- **DevOps Tools:** Docker, Kubernetes, Jenkins, Slack Integration  
- **Cloud:** AWS EKS (Elastic Kubernetes Service)  

## 📂 Project Structure
```
3-Tier-DevSecOps-Mega-Project/
│── api/                  # Node.js API
│── client/               # React frontend
│── jenkins/              # Jenkins pipelines (CI/CD, Slack setup)
│── k8s-prod/             # Kubernetes manifests
│── docker-compose.yaml   # Docker setup
│── eks-steps.md          # AWS EKS deployment guide
│── Jenkinsfile_CICD      # CI/CD pipeline
│── Jenkinsfile-slack     # Slack notification setup
└── README.md             # Project documentation
```

## ⚡ Quick Start (Local Setup)
### 1. Clone Repository
```bash
git clone https://github.com/jaiswaladi246/3-Tier-DevSecOps-Mega-Project.git
cd 3-Tier-DevSecOps-Mega-Project
```
### 2. Install Dependencies
```bash
cd api && npm install
cd ../client && npm install
```
### 3. Run Services
```bash
# Start API
cd api
npm start

# Start Client (in new terminal)
cd client
npm start
```
Visit 👉 `http://localhost:3000`

## 🐳 Run with Docker
```bash
docker-compose up --build
```
This will spin up **API + Client** containers and link them automatically.

## 🔄 CI/CD with Jenkins
- `Jenkinsfile_CICD` → Defines CI/CD pipeline (build → test → deploy)  
- `Jenkinsfile-slack` → Sends notifications to Slack channel  
- `Jenkins Slack Setup.pdf` → Step-by-step guide for integration  

## ☸️ Kubernetes & EKS
The repo includes `eks-steps.md` with a detailed guide:  
- Provisioning **EKS cluster** on AWS  
- Deploying API + Client with `k8s-prod` manifests  
- Scaling services dynamically  

## 🚧 Future Improvements
- Add **Terraform** for infrastructure as code  
- Implement **Helm charts** for better Kubernetes management  
- Enhance **monitoring** with Prometheus & Grafana  
- Add **automated testing** (unit + integration)  
- Improve **API documentation** using Swagger  

## 🤝 Contributing
Contributions are welcome!  
Please fork the repo, create a branch, and submit a PR.

## 📜 License
Distributed under the MIT License.  
See `LICENSE` for details.

<p align="center">⚡ Built with ❤️ using React, Node.js, Docker & Kubernetes ⚡</p>
