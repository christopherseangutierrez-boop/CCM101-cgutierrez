# ☁️ Laboratory 02: Build the Cloud Infrastructure Blueprint

> **Course:** CCM101 - Cloud Computing  
> **Institution:** University of Eastern Pangasinan — College of Information Technology  
> **Student:** Christopher Sean O. Gutierrez  
> **Repository:** [CCM101-cgutierrez](https://github.com/christopherseangutierrez-boop/CCM101-cgutierrez)  

---

## 📌 Executive Summary

This laboratory assignment focuses on inspecting core cloud infrastructure primitives using a Linux environment (KillerCoda). It covers evaluating hardware/software specifications, mapping kernel-level primitives to public cloud services, conducting a comparative analysis of top public cloud vendors (**AWS**, **Microsoft Azure**, **Google Cloud Platform**), and designing an architectural blueprint for cloud deployment.

---

## 🎯 Mission Objectives

- [x] **System Inspection:** Investigate virtualized hardware and OS metrics in a cloud server environment.
- [x] **Primitive Mapping:** Differentiate and categorize Compute, Storage, Networking, and OS components.
- [x] **Vendor Evaluation:** Conduct comparative analysis of core offerings across AWS, Azure, and GCP.
- [x] **Blueprint Design:** Draw and document a complete multi-tier cloud infrastructure architecture.
- [x] **Technical Documentation:** Publish professional Markdown technical reports in GitHub.

---

## 🛠️ Infrastructure Overview & Specifications

| Component | Detected Specification | Hardware / Kernel Context |
| :--- | :--- | :--- |
| **Operating System** | `Ubuntu 24.04.4 LTS` | Linux Kernel `6.8.0-138-generic` |
| **Compute Engine** | `Intel Xeon E312xx` | 1 vCPU @ 2.00GHz, 1.9 GiB RAM |
| **Storage Subsystem** | `19 GB` Virtual Block Disk | Mount point `/dev/vda1` on `/` |
| **Network Interface** | Dual Local Subnets | IP Addresses: `172.30.1.2`, `172.17.0.1` |

---

## 🧰 Tools & Technologies Executed

```bash
# Operating System & Kernel Version Verification
cat /etc/os-release | grep PRETTY_NAME
uname -r

# CPU & Memory Inspection
lscpu | grep -E "Model name|CPU\(s\):"
free -h

# Storage & File System Analysis
df -h /

# Hostname & Network Identity
hostname
hostname -I