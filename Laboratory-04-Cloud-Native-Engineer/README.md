# 🐳 Laboratory 04: The Cloud-Native Engineer

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Mission Overview
This mission explores the transition from traditional hardware virtualization (Virtual Machines) to modern containerization technologies using Docker[cite: 7]. Acting as a Cloud-Native Engineer at CloudNova Technologies, this laboratory covers container deployment, network port binding, container lifecycle management, and technical documentation[cite: 7].

---

## 🎯 Objectives
* Differentiate between Virtual Machines (VMs) and Containers[cite: 7].
* Access and verify a Docker-enabled Linux environment in KillerCoda[cite: 7].
* Execute core Docker CLI operations (pull, run, inspect, stop, remove)[cite: 7].
* Deploy an Nginx web server and expose host network ports[cite: 7].
* Document technical operations using professional Markdown[cite: 7].

---

## 💻 Executed Docker Commands

```bash
# Environment Verification
docker --version
docker info

# Image Acquisition & Container Launch
docker pull nginx
docker run -d -p 8080:80 --name my-nginx-server nginx
curl http://localhost:8080

# Lifecycle Management
docker ps
docker stop my-nginx-server
docker ps -a
docker rm my-nginx-server