# 📊 Host System Baseline Health Report

> **Role:** Cloud Operations / SRE Engineer — CloudNova Technologies  
> **Target Audience:** Engineering Operations Team  
> **Status:** `BASELINE VERIFIED`  

---

## 🖥️ Server Hardware Resource Metrics

| Resource Category | Measured System Value | Operational Status |
| :--- | :--- | :--- |
| **Total Available RAM** | ~1.9 GiB to 3.8 GiB (Depending on KillerCoda node specs) | `HEALTHY` |
| **Root File System Storage (/)** | ~20 GiB to 40 GiB Total Capacity | `HEALTHY` |
| **CPU Load Average** | Nominal baseline load under active monitoring (`top`) | `OPTIMAL` |

---

## 💡 Importance of Disk Space Monitoring

> **Why check disk space before traffic surges?**  
> Checking available disk storage is critical prior to a massive user traffic surge because high-traffic web applications rapidly generate extensive access
> logs, error logs, and session caches that can entirely consume remaining root volume storage, leading to complete system failure and service outages.
