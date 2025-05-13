# Birdwatcher

[GitHub Repository](https://github.com/milvus-io/birdwatcher)

**Category:** Data Integration & Migration  
**Tags:** debugging, milvus, management, open-source

## Description
Birdwatcher is an open-source system debugging tool designed for the Milvus vector database (version 2.0 or later). It provides advanced diagnostics to help developers and operators understand, troubleshoot, and manage Milvus deployments, ensuring robust vector search operations.

## Features
- **Connects to etcd:** Allows users to connect directly to the etcd instance used by Milvus for metadata storage.
- **Status Inspection:** Inspects and reports various statuses of the Milvus system.
- **Meta Inspection:** Provides commands to inspect and analyze metadata stored in etcd for debugging purposes.
- **Backup etcd Data:** Supports backing up etcd data for disaster recovery or migration.
- **Remote Instance Support:** Can connect to remote etcd instances, including those with custom base paths.
- **Command-line Interface:** Operates via CLI, providing flexible commands for diagnostics and management.
- **Help System:** Includes a help command to list and describe available commands.
- **Open-source:** Source code is available for customization and contributions.

## Installation
- Requires Go 1.18 or higher.
- Installation is recommended by cloning the source and building with Go, especially if the module uses replace or exclude directives.

## Pricing
Birdwatcher is open-source software and is available for free.