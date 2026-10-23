# 🛡️ Laboratory 08: The Cloud Security Engineer

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Mission Overview
This mission explores core cloud security principles and host-based defense in depth. Acting as a Cloud Security Engineer at CloudNova Technologies, this laboratory covers analyzing server attack surfaces, enforcing a Default Deny firewall policy, and managing precise port rules using Uncomplicated Firewall (UFW).

---

## 🎯 Objectives
* Explain core security concepts including the Principle of Least Privilege (PoLP) and Default Deny.
* Deploy web applications and verify endpoint accessibility.
* Safely configure host-based firewalls without locking out administrative access.
* Apply granular port permissions for containerized applications.
* Document security configurations professionally using Markdown.

---

## 💻 Commands Executed
```bash
# Application Deployment
docker run -d -p 8080:80 --name secure-web-app nginx
curl http://localhost:8080

# Firewall Hardening
sudo ufw allow ssh
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw allow 8080/tcp
sudo ufw status numbered
