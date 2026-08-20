
# 🌐 Major Cloud Provider Service Comparison

A comparative evaluation of equivalent core infrastructure primitives across the three dominant public cloud hyper-scalers: **Amazon Web Services (AWS)**, **Microsoft Azure**, and **Google Cloud Platform (GCP)**.

---

## 📊 Core Infrastructure Comparison Matrix

| Infrastructure Primitive | 🟠 Amazon Web Services (AWS) | 🔵 Microsoft Azure | 🟢 Google Cloud Platform (GCP) |
| :--- | :--- | :--- | :--- |
| **Virtual Compute** | Amazon EC2 | Azure Virtual Machines | Google Compute Engine (GCE) |
| **Object Storage** | Amazon S3 | Azure Blob Storage | Google Cloud Storage (GCS) |
| **Block Storage** | Amazon EBS | Azure Managed Disks | Google Persistent Disk |
| **Virtual Network** | Amazon VPC | Azure Virtual Network (VNet) | Google VPC |
| **Identity Management** | AWS IAM | Microsoft Entra ID *(Azure AD)* | Google Cloud IAM |
| **Managed Kubernetes** | Amazon EKS | Azure Kubernetes Service (AKS) | Google Kubernetes Engine (GKE) |

---

## ❓ Analytical Guide Questions

### 1. Which cloud provider offers the broadest range of services?
> **Amazon Web Services (AWS)** offers the broadest and most mature portfolio of cloud services globally. Being the pioneer in public cloud infrastructure (launched in 2006), AWS features the largest ecosystem, the highest market share, and an extensive array of niche enterprise solutions spanning satellite connectivity, quantum computing, and serverless architectures.

### 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products?
> **Microsoft Azure** is the strongly recommended cloud provider for Microsoft-centric enterprise environments. Azure offers seamless native identity sync via Active Directory/Entra ID, turn-key integration with Office 365/Windows Server ecosystems, and substantial cost savings through the Azure Hybrid Benefit program.

### 3. Which platform is widely recognized for AI, Machine Learning, and Kubernetes services?
> **Google Cloud Platform (GCP)** is globally recognized as the benchmark leader in AI, Data Analytics, and Kubernetes. Because Google originally engineered Kubernetes and open-sourced it, GCP’s **GKE (Google Kubernetes Engine)** offers industry-leading container orchestration alongside custom Tensor Processing Units (TPUs) and Vertex AI services.

### 4. What similarities did you observe among the three cloud providers?
> All three vendors share standard foundational primitives: virtualized compute instances, scalable object storage buckets, software-defined isolated networking (VPC/VNet), and granular access policies (IAM). Additionally, each provider operates under a pay-as-you-go pricing model with multi-zone geographic redundancy.
EOF