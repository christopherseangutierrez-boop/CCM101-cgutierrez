# 🏛️ Laboratory 06: The Cloud Deployment Engineer

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean O. Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Mission Overview
This mission explores Infrastructure as Code (IaC) principles by transitioning from manual container deployments to multi-tier orchestration using Docker Compose. Acting as a Cloud Deployment Engineer at CloudNova Technologies, this laboratory covers deploying a secure, self-hosted private cloud storage system (Nextcloud) backed by a relational database (MariaDB).

---

## 🎯 Objectives
* Explain multi-tier application architectures and container tier separation.
* Author structured YAML configuration files using CLI text editors.
* Orchestrate multi-container application stacks using Docker Compose.
* Route browser traffic to containerized web interfaces.
* Document Infrastructure as Code practices using professional Markdown.

---

## 💻 Commands Executed
```bash
# Project Setup & Configuration
mkdir -p ~/nextcloud-deployment && cd ~/nextcloud-deployment
nano docker-compose.yml

# Stack Orchestration & Management
docker-compose up -d
docker-compose ps
docker-compose down
