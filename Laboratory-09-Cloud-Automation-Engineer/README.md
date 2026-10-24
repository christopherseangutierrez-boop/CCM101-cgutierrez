# 🤖 Laboratory 09: The Cloud Automation Engineer

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Mission Overview
This final capstone mission explores cloud automation and DevOps principles. Acting as a Cloud Automation Engineer at CloudNova Technologies, 
this laboratory covers writing Bash automation scripts, managing executable file permissions, compressing directory archives, and configuring Linux cron jobs 
for autonomous task scheduling.

---

## 🎯 Objectives
* Write, format, and execute functional Bash scripts using terminal text editors.
* Modify file permissions using `chmod`
* Compress directory structures dynamically using timestamped tarballs.
* Configure Linux `crontab` schedules for recurring background operations.
* Complete and finalize a comprehensive GitHub Cloud Computing Portfolio.

---

## 💻 Commands Executed
```bash
# Script Creation & Execution
mkdir -p ~/app-data && echo "This is critical client data." > ~/app-data/data.txt
nano backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/

# Cron Scheduling
crontab -l
env EDITOR=nano crontab -e
crontab -l
