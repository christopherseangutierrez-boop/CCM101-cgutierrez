# ⚙️ Automated Backup Script & Cron Scheduling Guide

> **Engineer:** Christopher Sean Gutierrez  
> **Environment:** KillerCoda Ubuntu Playground  
> **Project:** Automated Infrastructure Backup Routine  

---

## 📜 Full `backup.sh` Source Code
```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies
SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")
echo "Initiating automated backup..."
mkdir -p $BACKUP_DIR
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR
echo "Backup completed successfully at $TIMESTAMP!"
