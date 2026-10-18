# Linux System Health Monitor & Automated Backup Engine

A production-ready Bash script designed for Linux SysAdmins and DevOps Engineers to automate system metric monitoring (CPU, RAM, Disk) and perform automated configuration backups with rotation policies.

## Features
- **Real-time Metrics Assessment**: Checks CPU, Memory, and Storage against configurable safety thresholds.
- **Automated Disaster Recovery Backup**: Compresses critical configuration directories (`Nginx`, `SSH`, etc.).
- **Log Management**: Generates timestamped logs with standard severity levels (`INFO`, `WARNING`, `CRITICAL`).
- **Retention Policy**: Automatically cleans up archives older than 7 days to prevent disk exhaustion.

## Usage
```bash
chmod +x server_health_backup.sh
./server_health_backup.sh
