# 🏛️ Multi-Tier Architecture Research Report

> **Role:** Cloud Deployment Engineer — CloudNova Technologies  
> **Target Audience:** Client Technical Architecture Team  
> **Status:** `ARCHITECTURE APPROVED`  

---

## 🏗️ Two-Tier Architecture Breakdown

### 1. The Web/Application Tier
* **Role:** Serves as the user-facing interface layer (Nextcloud). It handles incoming HTTP/HTTPS requests from clients, processes user interactions, renders the web GUI, and manages file transfer streams.

### 2. The Database Tier
* **Role:** Serves as the persistent backend data storage layer (MariaDB). It securely stores structured relational data, user credentials, permission maps, folder structures, and system configuration metadata.

---

## 💡 Why Separate the Tiers?

> **Decoupling Application and Data:**  
> Separating the web application server and the database into two distinct, communicating containers rather than packing them into
>  a single monolithic instance is essential for scalability, maintainability, and security. If the web container experiences a traffic spike,
>  high resource loads, or software failure, it can be restarted, scaled, or replaced independently without corrupting or losing the underlying database
>  state. Furthermore, this isolation restricts direct public access to the database, ensuring that sensitive data remains shielded behind the internal container
>  network.
