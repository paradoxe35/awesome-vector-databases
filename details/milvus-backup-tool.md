# Milvus Backup Tool

Milvus Backup Tool provides backup and restore functionalities for Milvus vector databases, ensuring data safety and disaster recovery capabilities.

- **Source:** [GitHub Repository](https://github.com/zilliztech/milvus-backup)
- **Category:** Data Integration & Migration
- **Tags:** milvus, backup, restore, disaster-recovery

## Features

- **Backup and Restore:** Enables backup and restoration of Milvus data with minimal impact on Milvus performance. The cluster remains operational during these processes.
- **Multiple Interfaces:** Usable via command-line interface (CLI) or as a REST API server.
- **Flexible Storage Support:** Supports various storage backends for both primary and backup storage, including local, MinIO, S3, AWS, GCP, Aliyun, Azure, Tencent Cloud.
- **Cross-Storage Backup:** Allows for cross-storage backups (e.g., MinIO to AWS S3, S3 to local, or S3 A to S3 B).
- **RBAC Backup & Restore:** Supports backup and restore of RBAC metadata with additional parameters.
- **Configurable Parallelism:** Adjustable parallelism for backup and restore operations at collection and thread-pool levels.
- **Garbage Collection Handling:** Can pause Milvus garbage collection during backup to ensure consistency.
- **API Documentation:** Swagger UI is available for REST API usage details.
- **Comprehensive Configuration:** All operational parameters are configurable via a YAML file (`backup.yaml`), including logging, Milvus connection, storage configuration, backup settings, and advanced options.
- **Minimal Performance Impact:** Designed to have negligible effect on Milvus cluster performance during operation.
- **Temporary File Management:** Optionally keep or delete temporary files during restore for debugging purposes.
- **Multiple Installation Methods:** Available as downloadable binaries and via Homebrew for Mac.

## Pricing

- **Open Source:** Milvus Backup Tool is released under the Apache License, Version 2.0, and is free to use.
