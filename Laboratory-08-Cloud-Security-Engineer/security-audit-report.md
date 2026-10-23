# 🛡️ Security Audit & Threat Analysis Report

> **Role:** Cloud Security Engineer — CloudNova Technologies  
> **Target Audience:** Enterprise Security Operations Team  
> **Status:** `SECURITY REVIEW COMPLETED`  

---

## 🔒 Core Cloud Security Concepts

### 1. The Principle of Least Privilege (PoLP)
* **Definition & Importance:** The Principle of Least Privilege dictates that user accounts, processes, and systems should be granted only the absolute minimum permissions and access rights necessary to perform their specific tasks. This is vital in cloud environments because it ensures that if a user account or service credential is compromised, the attacker's blast radius is strictly contained, preventing unauthorized lateral movement across the rest of the infrastructure.

### 2. Attack Surface
* **Definition & Importance:** The attack surface refers to the sum total of all potential vulnerabilities, open network ports, entry points, and attack vectors through which an unauthorized user can try to access or extract data from a virtual machine or cloud environment. Minimizing the attack surface by closing unnecessary ports and services is critical to reducing overall system risk.

### 3. Default Deny Policy
* **Definition & Importance:** A Default Deny security posture automatically blocks all incoming network traffic unless an explicit rule has been created to allow it. It is fundamentally safer than trying to blacklist individual malicious actors because new threats emerge constantly; blocking everything by default ensures that only explicitly verified and authorized communication channels are ever permitted.
