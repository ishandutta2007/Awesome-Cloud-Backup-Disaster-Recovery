# Awesome-Cloud-Backup-Disaster-Recovery

# Awesome-Cloud-Backup-Disaster-Recovery

# Awesome-Cloud-Backup-Disaster-Recovery

## Top Cloud Backup & Disaster Recovery Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SaaS Data Protection, Ransomware Resilience & Business Continuity*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Backup & Disaster Recovery**. These tools protect critical business data across SaaS applications, cloud infrastructure, and hybrid environments—enabling granular recovery, ransomware rollback, and compliance-ready retention.



**Examples** include Salesforce Backup, OwnBackup (Own), Spanning Backup, Odaseva, Veeam Backup for Salesforce, Keepit, Rewind, Druva inSync, HYCU, and AvePoint Cloud Backup (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom backup orchestration, and open data resilience—ideal for organizations seeking transparent, vendor-independent protection for PostgreSQL, Linux systems, cloud infrastructure, and SaaS data.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Backup](https://www.salesforce.com/)**  

  Native Salesforce data backup and recovery service providing daily automated backups with configurable retention and metadata restoration.



- **[OwnBackup (Own)](https://www.ownbackup.com/)**  

  Leading Salesforce backup and recovery platform with automated daily backups, sandbox seeding, and intelligent recovery for metadata and data.



- **[Spanning Backup](https://spanning.com/)**  

  SaaS data protection for Microsoft 365, Google Workspace, and Salesforce. Automated daily backups with granular restore and ransomware recovery .



- **[Odaseva](https://odaseva.com/)**  

  Enterprise Salesforce data protection platform with backup, archiving, and compliance capabilities for large-scale Salesforce environments.



- **[Veeam Backup for Salesforce](https://www.veeam.com/)**  

  Salesforce backup and recovery with granular restore, metadata protection, and integration into Veeam's broader data platform ecosystem.



- **[Keepit](https://www.keepit.com/)**  

  Independent cloud backup for Microsoft 365, Google Workspace, and Salesforce with immutable data storage and enterprise-grade security.



- **[Rewind](https://rewind.com/)**  

  Backup and recovery for Shopify, BigCommerce, and other SaaS platforms with automated backups and one-click restore .



- **[Druva inSync](https://www.druva.com/)**  

  Cloud-native SaaS data protection with endpoint backup, Microsoft 365 protection, and ransomware resilience .



- **[HYCU](https://www.hycu.com/)**  

  Multi-cloud backup and recovery for Nutanix, VMware, and SaaS applications including Microsoft 365 and Salesforce .



- **[AvePoint Cloud Backup](https://www.avepoint.com/)**  

  Enterprise SaaS backup for Microsoft 365, Google Workspace, Salesforce, and Dynamics 365 with compliance-focused retention .



## Open-Source GitHub Projects



- **[Plakar](https://github.com/PlakarKorp/plakar)**  

  Innovative open-source backup platform (ISC license) built around the "Kloset" format. Features end-to-end encryption with zero-knowledge architecture, source-side deduplication and compression, immutable snapshots, and support for files, objects, databases, and SaaS connectors. Integrates with S3, NAS, tape, and Kubernetes volumes. Enterprise edition adds multi-store orchestration and RBAC .



- **[Relax-and-Recover (ReaR)](https://github.com/rear/rear)**  

  The leading open-source disaster recovery and system migration solution (GPL). Modular framework producing bootable rescue images with support for ISO, PXE, USB, and OBDR tape. Integrates with numerous backup backends including Borg, Bacula, Bareos, Duplicity, rsync, TSM, NetBackup, and Data Protector .



- **[Barman](https://github.com/EnterpriseDB/barman)**  

  Backup and Recovery Manager for PostgreSQL (GPL-3.0), maintained by EnterpriseDB. Enables remote backups of multiple PostgreSQL servers in business-critical environments, reducing risk and supporting DBAs during recovery .



- **[BorgBackup](https://github.com/borgbackup/borg)**  

  Deduplicating backup program with compression and authenticated encryption (BSD license). Highly efficient for server and workstation backups with mountable archives and prune-based retention.



- **[Vanguard](https://github.com/Kadantte/vanguards)**  

  Open-source Laravel-based backup solution (AGPL-3.0) for files and databases. Features intuitive web UI, flexible scheduling, multi-channel notifications (Email, Discord, Slack, Pushover), OAuth login with 2FA, REST API, and encrypted storage .



- **[Snapr](https://github.com/maximseshuk/snapr)**  

  Modern open-source backup tool (MIT) written in Go. Supports PostgreSQL, MySQL, MariaDB, MongoDB, Redis, and SQLite dumps plus plain files. Features compression, OpenSSL encryption, retention policies, notifications via webhook/Telegram/email, web UI, and REST API .



- **[BackupSheep](https://github.com/bilal414/backupsheep)**  

  Open-source backup automation platform (license varies) for websites and databases. Features one-click restores, no silent partial backups, disk-space preflight checks, resume-friendly transfers, credential encryption, and Slack/Telegram notifications. Verified at 100k+ file scale .



- **[DaliBackup-OSS](https://github.com/daliranas/DaliBackup-OSS)**  

  Lightweight, sovereign backup and disaster recovery orchestration (Docker-ready). Supports Microsoft Hyper-V (VSS-consistent), Proxmox VE (QEMU & LXC), and IMAP mailbox backup. Features zero-trust AES-256-GCM encryption, embedded SQLite database, and multi-protocol storage (POSIX, NFS, SFTP, FTP) .



- **[Stronghold](https://github.com/mehdi-arfaoui/stronghold)**  

  Open-source disaster recovery automation platform for cloud infrastructure (AWS-first, Azure planned). Features recovery contract verification, RTO/RPO validation with evidence-based verdicts, dependency graph construction, SPOF detection, and CI/CD integration for enforced DR compliance .



- **[CloudRecovery](https://pypi.org/project/cloudrecovery/)**  

  AI-assisted incident recovery tool (Python) with runbook automation, policy-guarded execution, and safe triage modes. Integrates with OpenShift/Kubernetes for crashloop recovery and site-down scenarios .



### Additional Strong Open-Source Options



- **[Duplicity](https://gitlab.com/duplicity/duplicity)** — Encrypted bandwidth-efficient backup using rsync algorithm.

- **[Restic](https://github.com/restic/restic)** — Fast, secure, cross-platform backup program with deduplication and encryption.

- **[Kopia](https://github.com/kopia/kopia)** — Fast and secure open-source backup/restore tool with end-to-end encryption.

- **[UrBackup](https://github.com/uroni/urbackup_backend)** — Open-source client/server backup system for Windows, Linux, and macOS.

- **[Bacula](https://github.com/bacula-web/bacula-web)** / **[Bareos](https://github.com/bareos/bareos)** — Enterprise-grade open-source backup and recovery platforms.

- Community **Ansible** and **Terraform** modules for infrastructure-as-code backup orchestration.



**Frameworks for building custom systems**: Combine **Barman** for PostgreSQL DR with **BorgBackup** for file-level deduplication, **ReaR** for bare-metal recovery images, **Plakar** for SaaS/Kubernetes workloads, and **Stronghold** for cloud DR contract validation — creating a fully self-hosted enterprise backup and recovery stack.



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
