# Awesome-Cloud-Backup-Disaster-Recovery

## Top Cloud Backup & Disaster Recovery Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on SaaS Data Protection, Ransomware Resilience & Business Continuity*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Backup & Disaster Recovery**. These tools protect critical business data across SaaS applications, cloud infrastructure, and hybrid environments—enabling granular recovery, ransomware rollback, and compliance-ready retention.

**Examples** include Salesforce Backup, OwnBackup (Own), Spanning Backup, Odaseva, Veeam Backup for Salesforce, Keepit, Rewind, Druva inSync, HYCU, and AvePoint Cloud Backup (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosting, custom backup orchestration, and open data resilience—ideal for organizations seeking transparent, vendor-independent protection for Kubernetes, PostgreSQL, Linux systems, cloud storage, and SaaS data.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing / Free Tier |
|---|---|---|
| **[Salesforce Backup](https://www.salesforce.com/)** | Native Salesforce data backup and recovery service providing daily automated backups with configurable retention and metadata restoration. | Paid add-on (based on Salesforce user licenses/storage); contact sales for quotes. No free tier. |
| **[OwnBackup (Own)](https://www.ownbackup.com/)** | Leading Salesforce backup and recovery platform with automated daily backups, sandbox seeding, and intelligent recovery for metadata and data. | Custom enterprise pricing per user/month; free demo/trial available on request. |
| **[Spanning Backup](https://spanning.com/)** | SaaS data protection for Microsoft 365, Google Workspace, and Salesforce. Automated daily backups with granular restore and ransomware recovery. | Starts at ~$3–$4/user/month (annual commitment). 14-day free trial available. |
| **[Odaseva](https://odaseva.com/)** | Enterprise Salesforce data protection platform with backup, archiving, and compliance capabilities for large-scale Salesforce environments. | Enterprise custom pricing based on org size and storage requirements. No public free tier. |
| **[Veeam Backup for Salesforce](https://www.veeam.com/)** | Salesforce backup and recovery with granular restore, metadata protection, and integration into Veeam's broader data platform ecosystem. | Free community edition available up to 50 user licenses; commercial subscription pricing thereafter. |
| **[Keepit](https://www.keepit.com/)** | Independent cloud backup for Microsoft 365, Google Workspace, and Salesforce with immutable data storage and enterprise-grade security. | Per-seat subscription pricing with unlimited storage and retention; 30-day free trial. |
| **[Rewind](https://rewind.com/)** | Backup and recovery for Shopify, BigCommerce, GitHub, Jira, and QuickBooks with automated backups and one-click restore. | Plans start from ~$9/month for small stores/accounts; 7-day to 14-day free trial available. |
| **[Druva inSync](https://www.druva.com/)** | Cloud-native SaaS data protection with endpoint backup, Microsoft 365 protection, and ransomware resilience. | Tiered pricing per user/month (Business, Enterprise, Elite); 30-day free trial available. |
| **[HYCU](https://www.hycu.com/)** | Multi-cloud backup and recovery for Nutanix, VMware, and SaaS applications including Microsoft 365, Jira, and Salesforce. | Usage-based / per-workload pricing; free tier/trial available for selected SaaS connectors via R-Cloud. |
| **[AvePoint Cloud Backup](https://www.avepoint.com/)** | Enterprise SaaS backup for Microsoft 365, Google Workspace, Salesforce, and Dynamics 365 with compliance-focused retention. | Per-user subscription pricing; 30-day free trial available. |

## Open-Source GitHub Projects

- **[Rclone](https://github.com/rclone/rclone)** [![GitHub stars](https://img.shields.io/github/stars/rclone/rclone?style=social&color=white)](https://github.com/rclone/rclone/stargazers)  
  Command-line program to manage files on cloud storage ("rsync for cloud storage"). Supports over 70 cloud storage providers including S3, Google Drive, Azure Blob, Dropbox, Backblaze B2, and SFTP with sync, transfer, crypt, and mount capabilities.

- **[Restic](https://github.com/restic/restic)** [![GitHub stars](https://img.shields.io/github/stars/restic/restic?style=social&color=white)](https://github.com/restic/restic/stargazers)  
  Fast, secure, cross-platform backup program written in Go. Features authenticated cryptography, deduplication, snapshots, and native support for local storage, SFTP, REST, S3, MinIO, Azure Blob, and Google Cloud Storage.

- **[Kopia](https://github.com/kopia/kopia)** [![GitHub stars](https://img.shields.io/github/stars/kopia/kopia?style=social&color=white)](https://github.com/kopia/kopia/stargazers)  
  Fast and secure open-source backup and restore tool for Windows, macOS, and Linux. Features end-to-end encryption, deduplication, compression, scheduling, CLI, and desktop/web GUI with multi-cloud target support.

- **[BorgBackup](https://github.com/borgbackup/borg)** [![GitHub stars](https://img.shields.io/github/stars/borgbackup/borg?style=social&color=white)](https://github.com/borgbackup/borg/stargazers)  
  Deduplicating backup program with compression and authenticated encryption (BSD license). Highly efficient for server and workstation backups with mountable archives, append-only mode, and prune-based retention.

- **[Velero](https://github.com/vmware-tanzu/velero)** [![GitHub stars](https://img.shields.io/github/stars/vmware-tanzu/velero)](https://github.com/vmware-tanzu/velero/stargazers)  
  Cloud-native disaster recovery, data protection, and migration platform for Kubernetes cluster resources and persistent volumes, supporting major public clouds and on-premises storage plugins.

- **[Longhorn](https://github.com/longhorn/longhorn)** [![GitHub stars](https://img.shields.io/github/stars/longhorn/longhorn?style=social&color=white)](https://github.com/longhorn/longhorn/stargazers)  
  Cloud-Native distributed block storage system for Kubernetes with built-in snapshot, incremental backup to secondary storage (S3/NFS), and cross-cluster disaster recovery volume replication.

- **[pgBackRest](https://github.com/pgbackrest/pgbackrest)** [![GitHub stars](https://img.shields.io/github/stars/pgbackrest/pgbackrest?style=social&color=white)](https://github.com/pgbackrest/pgbackrest/stargazers)  
  Reliable, high-performance backup and restore solution for PostgreSQL. Supports full, differential, and incremental backups, parallel compression and transfer, delta restore, encryption, and direct S3/Azure/GCS streaming.

- **[WAL-G](https://github.com/wal-g/wal-g)** [![GitHub stars](https://img.shields.io/github/stars/wal-g/wal-g?style=social&color=white)](https://github.com/wal-g/wal-g/stargazers)  
  Archival and restoration tool for databases in the cloud. Successor to WAL-E, written in Go, supporting PostgreSQL, MySQL, MongoDB, Redis, and FoundationDB with point-in-time recovery and cloud storage streaming.

- **[Barman](https://github.com/EnterpriseDB/barman)** [![GitHub stars](https://img.shields.io/github/stars/EnterpriseDB/barman?style=social&color=white)](https://github.com/EnterpriseDB/barman/stargazers)  
  Backup and Recovery Manager for PostgreSQL (GPL-3.0), maintained by EnterpriseDB. Enables remote backups of multiple PostgreSQL servers in business-critical environments with zero-data-loss point-in-time recovery.

- **[Plakar](https://github.com/PlakarKorp/plakar)** [![GitHub stars](https://img.shields.io/github/stars/PlakarKorp/plakar?style=social&color=white)](https://github.com/PlakarKorp/plakar/stargazers)  
  Innovative open-source backup platform (ISC license) built around the "Kloset" format. Features end-to-end encryption with zero-knowledge architecture, source-side deduplication, immutable snapshots, and support for files, objects, databases, and SaaS connectors.

- **[Bareos](https://github.com/bareos/bareos)** [![GitHub stars](https://img.shields.io/github/stars/bareos/bareos?style=social&color=white)](https://github.com/bareos/bareos/stargazers)  
  Cross-network enterprise open-source backup solution (AGPL-3.0) which preserves, archives, and recovers data from all major operating systems, supporting disk, cloud, and tape storage.

- **[Relax-and-Recover (ReaR)](https://github.com/rear/rear)** [![GitHub stars](https://img.shields.io/github/stars/rear/rear?style=social&color=white)](https://github.com/rear/rear/stargazers)  
  The leading open-source bare-metal disaster recovery and system migration solution for Linux (GPL). Produces bootable rescue media (ISO, PXE, USB) and integrates with Borg, Bacula, Bareos, Duplicity, rsync, and enterprise backends.

- **[UrBackup](https://github.com/uroni/urbackup_backend)** [![GitHub stars](https://img.shields.io/github/stars/uroni/urbackup_backend?style=social&color=white)](https://github.com/uroni/urbackup_backend/stargazers)  
  Client/server open-source network backup system for Windows, macOS, and Linux with both file-level and image-level backups without interrupting running tasks.

- **[Kanister](https://github.com/kanisterio/kanister)** [![GitHub stars](https://img.shields.io/github/stars/kanisterio/kanister?style=social&color=white)](https://github.com/kanisterio/kanister/stargazers)  
  CNCF sandbox framework for application-level data management on Kubernetes. Enables blueprint-driven backup, restore, and disaster recovery tasks customized to specific stateful databases and workloads.

- **[BackupSheep](https://github.com/bilal414/backupsheep)** [![GitHub stars](https://img.shields.io/github/stars/bilal414/backupsheep?style=social&color=white)](https://github.com/bilal414/backupsheep/stargazers)  
  Open-source backup automation platform for websites and databases. Features one-click restores, disk-space preflight checks, resume-friendly transfers, credential encryption, and Slack/Telegram notifications.

- **[Bacula-Web](https://github.com/bacula-web/bacula-web)** [![GitHub stars](https://img.shields.io/github/stars/bacula-web/bacula-web?style=social&color=white)](https://github.com/bacula-web/bacula-web/stargazers)  
  Open-source web-based monitoring and reporting dashboard for Bacula backup infrastructure, providing real-time visibility into backup jobs, pools, and storage status.

- **[Stronghold](https://github.com/mehdi-arfaoui/stronghold)** [![GitHub stars](https://img.shields.io/github/stars/mehdi-arfaoui/stronghold?style=social&color=white)](https://github.com/mehdi-arfaoui/stronghold/stargazers)  
  Open-source disaster recovery automation platform for cloud infrastructure. Features recovery contract verification, RTO/RPO validation with evidence-based verdicts, dependency graph construction, SPOF detection, and CI/CD integration.

- **[Snapr](https://github.com/maximseshuk/snapr)** [![GitHub stars](https://img.shields.io/github/stars/maximseshuk/snapr?style=social&color=white)](https://github.com/maximseshuk/snapr/stargazers)  
  Modern open-source backup tool (MIT) written in Go. Supports PostgreSQL, MySQL, MariaDB, MongoDB, Redis, and SQLite dumps plus plain files. Features compression, OpenSSL encryption, retention policies, notifications, and web UI.

- **[Vanguard](https://github.com/Kadantte/vanguards)** [![GitHub stars](https://img.shields.io/github/stars/Kadantte/vanguards?style=social&color=white)](https://github.com/Kadantte/vanguards/stargazers)  
  Open-source Laravel-based backup solution (AGPL-3.0) for files and databases. Features intuitive web UI, flexible scheduling, multi-channel notifications (Email, Discord, Slack, Pushover), OAuth login with 2FA, REST API, and encrypted storage.

- **[DaliBackup-OSS](https://github.com/daliranas/DaliBackup-OSS)** [![GitHub stars](https://img.shields.io/github/stars/daliranas/DaliBackup-OSS?style=social&color=white)](https://github.com/daliranas/DaliBackup-OSS/stargazers)  
  Lightweight sovereign backup and disaster recovery orchestration (Docker-ready). Supports Microsoft Hyper-V (VSS-consistent), Proxmox VE (QEMU & LXC), and IMAP mailbox backup with AES-256-GCM encryption.

---

### Non-GitHub Open-Source Tools & Frameworks

- **[Duplicity](https://gitlab.com/duplicity/duplicity)** — Encrypted bandwidth-efficient backup using rsync algorithm (hosted on GitLab).
- **[CloudRecovery](https://pypi.org/project/cloudrecovery/)** — AI-assisted incident recovery tool (Python) with runbook automation and policy-guarded execution.

**Frameworks for building custom systems**: Combine **Barman** or **pgBackRest** for database DR with **BorgBackup** / **Restic** / **Kopia** for deduplicated file/object snapshots, **Velero** or **Longhorn** for Kubernetes cloud resilience, and **ReaR** for bare-metal system recovery — creating a fully self-hosted enterprise backup and recovery stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Backup and recovery data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).
- Self-hosted open-source solutions require proper security hardening, encryption key management, and tested recovery procedures.

---

**Made for IT teams, DBAs, DevOps engineers, and developers building transparent data resilience solutions.**  
Let's make cloud backup and disaster recovery more open, data-driven, and resilient.
