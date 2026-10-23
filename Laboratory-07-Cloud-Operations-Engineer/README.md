# 🔍 Laboratory 07: The Cloud Operations Engineer

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean O. Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Mission Overview
This mission focuses on site reliability engineering (SRE) and cloud observability[cite: 14]. Acting as a Cloud Operations Engineer at CloudNova Technologies, this laboratory covers establishing system hardware baselines, deploying web containers, simulating user traffic, analyzing application log files, and monitoring real-time resource utilization metrics[cite: 14, 15, 17].

---

## 🎯 Objectives
* Utilize native Linux CLI utilities (`free`, `df`, `top`) to monitor host resource capacity.
* Deploy an Nginx web server and simulate HTTP traffic queries.
* Extract and evaluate application log files to isolate HTTP error codes (`200` vs `404`)[cite: 17].
* Monitor live container performance streams using `docker stats`[cite: 17].
* Document server health and observability procedures using Markdown[cite: 15].

---

## 💻 Monitoring & Deployment Commands Executed
```bash
# Hardware Baseline Checks
free -h
df -h
top

# Application Deployment & Traffic Simulation
docker run -d -p 8080:80 --name client-website nginx
curl http://localhost:8080
curl http://localhost:8080/hidden-admin-page

# Observability & Metrics
docker logs client-website
docker stats
