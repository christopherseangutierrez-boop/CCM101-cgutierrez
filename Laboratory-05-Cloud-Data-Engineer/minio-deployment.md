# 🚀 MinIO Object Storage Server Deployment Guide

> **Engineer:** Christopher Sean Gutierrez  
> **Environment:** KillerCoda Ubuntu Playground  
> **Service:** MinIO S3-Compatible Object Storage  

---

## 🛠️ Deployment Configuration

### 1. Docker Execution Command

 Run MinIO server container with custom ports and environment variables

 docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
  pgsty/minio server /data --console-address ":9001"

# ------------------------------------------------------------
### 2. Configuration Parameters & Port Mappings
API Port (9000): Handles programmatic S3 API calls from clients, SDKs, and ingestion tools.
 Web Console Port (9001): Provides the admin GUI dashboard for bucket management and monitoring.
 Bucket Created: client-photos
# ------------------------------------------------------------

### 3. Explanation of the -e (Environment Variable) Flags
 - MINIO_ROOT_USER=cloudadmin
   Sets the administrative root username for the MinIO server.
   Used to log into the Web Console and authenticate API operations.

 - MINIO_ROOT_PASSWORD=CloudNova2026!
   Defines the root account password.
   Secures the cluster against unauthorized access, ensuring only admins can manage buckets, keys, and policies.
# ------------------------------------------------------------
