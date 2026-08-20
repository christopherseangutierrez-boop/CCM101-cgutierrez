# 📊 Cloud Infrastructure Assessment Report

> **Target Environment:** KillerCoda Cloud Sandbox  
> **Assigned Engineer:** Christopher Sean Gutierrez  
> **Status:** `VERIFIED`  

---

## 1. System Overview

| Parameter | Observed Metric |
| :--- | :--- |
| **System Hostname** | `ubuntu` |
| **Operating System** | `Ubuntu 24.04.4 LTS` |
| **Kernel Release** | `6.8.0-138-generic` |
| **Architecture** | `x86_64` |

---

## 2. Compute Infrastructure

| Component | Details |
| :--- | :--- |
| **CPU Model** | Intel(R) Xeon(R) CPU E312xx (Sandy Bridge, IBRS update) |
| **Clock Speed** | `2.00 GHz` |
| **Allocated Cores** | `1 vCPU` |
| **Total Memory (RAM)** | `1.9 GiB` |
| **Active Memory Usage** | `414 MiB Used` / `874 MiB Free` / `781 MiB Buffer/Cache` |

---

## 3. Storage & File System Architecture

| Storage Metric | Value |
| :--- | :--- |
| **Primary Block Device** | `/dev/vda1` |
| **Mount Point** | `/` (Root) |
| **Total Disk Volume** | `19 GB` |
| **Utilized Storage** | `5.4 GB` (`30%`) |
| **Available Storage** | `13 GB` |

---

## 4. Network Configuration & Topology

| Network Parameter | Value |
| :--- | :--- |
| **Primary Internal IP** | `172.30.1.2` |
| **Secondary / Docker Bridge IP** | `172.17.0.1` |
| **Loopback Address** | `127.0.0.1` |

---

> 📝 **Assessment Summary:** The target environment represents a lightweight virtual private server (VPS) running on top of KVM hypervisors. The resource configuration provides adequate capacity for dev/test container workloads and microservice prototyping.