# 🏛️ Laboratory 06: The Cloud Deployment Engineer

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean O. Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Mission Overview
This mission explores Infrastructure as Code (IaC) principles by transitioning from manual container deployments to multi-tier orchestration using Docker Compose. Acting as a Cloud Deployment Engineer at CloudNova Technologies, this laboratory covers deploying a secure, self-hosted private cloud storage system (Nextcloud) backed by a relational database (MariaDB)[cite: 10, 11].

---

## 🎯 Objectives
* Explain multi-tier application architectures and container tier separation[cite: 9, 10].
* Author structured YAML configuration files using CLI text editors[cite: 10, 11].
* Orchestrate multi-container application stacks using Docker Compose[cite: 10, 11].
* Route browser traffic to containerized web interfaces[cite: 12, 13].
* Document Infrastructure as Code practices using professional Markdown[cite: 10, 13].

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
