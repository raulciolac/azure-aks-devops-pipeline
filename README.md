# Azure AKS DevOps Pipeline

## Overview
This project demonstrates a complete DevOps workflow using Azure Kubernetes Service (AKS), Terraform, Docker, and GitHub Actions.

## Features
- Infrastructure provisioning with Terraform
- Kubernetes deployment on AKS
- Docker containerization
- CI/CD pipeline using GitHub Actions

## Tech Stack
- Azure (AKS)
- Terraform
- Docker
- Kubernetes
- GitHub Actions

## Project Structure
app/ - application code  
docker/ - Dockerfile  
k8s/ - Kubernetes manifests  
terraform/ - infrastructure as code  
.github/workflows/ - CI/CD pipeline  

## Workflow
1. Code is pushed to GitHub  
2. GitHub Actions builds Docker image  
3. Image is pushed to Docker Hub  
4. Kubernetes deploys the application  

## Notes
Replace YOUR_DOCKERHUB/aks-app with your Docker Hub username and repository name (e.g. username/aks-app).

## Author
Raul Ciolac
