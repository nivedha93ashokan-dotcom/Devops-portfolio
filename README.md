# DevOps Demo App 🚀

A complete DevOps CI/CD project demonstrating containerization, automated Docker image builds, Docker Hub publishing, and Kubernetes deployment using GitHub Actions.

## 🏗️ Architecture

Developer
   ↓
GitHub Repository
   ↓
GitHub Actions
   ↓
Docker Build
   ↓
Docker Hub
   ↓
Kubernetes / Minikube
   ↓
Running Application

## 🛠️ Technologies

- Python / Flask
- Docker
- Docker Hub
- Kubernetes
- Minikube
- kubectl
- GitHub Actions
- Git / GitHub

## 📁 Project Structure

```text
devops-portfolio/
├── .github/
│   └── workflows/
│       └── ci-cd.yml
│
├── projects/
│   └── devops-demo-app/
│       ├── app/
│       │   └── app.py
│       ├── Dockerfile
│       ├── requirements.txt
│       └── kubernetes/
│           ├── deployment.yaml
│           └── service.yaml
│
└── README.md
