cd ~/CCM101-cgutierrez/Laboratory-05-Cloud-Data-Engineer

cat << 'EOF' > storage-types-research.md
# 🗄️ Types of Cloud Storage Research Report

> **Role:** Cloud Data Engineer — CloudNova Technologies  
> **Target Audience:** Client Technical Architecture Team  
> **Status:** `RESEARCH VERIFIED`  

---

## 📊 Cloud Storage Types Comparison Matrix

| Storage Type | Description (How it stores data) | Primary Use Case | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Data is split into raw, fixed-size blocks with unique identifiers. Formatted with file systems like ext4 or NTFS. | High-performance database storage, boot volumes, and transactional workloads requiring low-latency read/write operations. | AWS EBS, Azure Managed Disks, GCP Persistent Disk |
| **File Storage** | Data is organized in a hierarchical structure of files and folders within a shared directory tree over a network (NFS/SMB). | Shared corporate file directories, multi-user content management systems, and legacy application shared storage. | AWS EFS, Azure Files, GCP Filestore |
| **Object Storage** | Data is managed as discrete objects consisting of data, custom metadata, and a unique URL key within a flat namespace. | Storing massive pools of unstructured data like user media uploads, backups, data lakes, and static web assets. | AWS S3, Azure Blob Storage, Google Cloud Storage |

---

## 💡 Client Recommendation Summary

> **Why Object Storage for Your Photo-Sharing Application?**  
> Object Storage is the optimal choice for storing millions of user-uploaded images because of its limitless scalability, flat namespace architecture, and cost-effectiveness for unstructured data. Unlike block storage, which is bound to specific virtual machine instances, object storage provides high durability and direct HTTP accessibility via unique keys. This allows your application to handle rapid growth without architectural bottlenecks.
EOF