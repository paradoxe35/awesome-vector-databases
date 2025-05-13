# Milvus CDC

[Milvus CDC](https://github.com/zilliztech/milvus-cdc) is an open-source change data capture tool designed specifically for Milvus, a vector database. It enables capturing changes from upstream Milvus collections and synchronizing them to downstream Milvus instances. This facilitates data reliability, reduces the risk of data loss, and supports disaster recovery scenarios.

## Features
- **Change Data Capture for Milvus:** Captures changes (such as inserts, updates, deletes) from source Milvus collections.
- **Synchronization:** Sinks captured changes to target (downstream) Milvus clusters, supporting active-standby architectures for disaster recovery.
- **Data Reliability:** Helps reduce the probability of data loss by keeping downstream collections up-to-date.
- **HTTP Server:** Provides an HTTP interface for creating and managing CDC tasks, controlling execution, and maintaining meta-information.
- **Core Library (corelib):** Handles the execution of synchronization tasks, including:
  - **Reader:** Reads metadata and data changes from etcd and message queues (mq) in the source Milvus cluster.
  - **Writer:** Converts message queue data into Milvus API parameters and sends them to the target Milvus.
- **Task Workflow:**
  1. User creates CDC task via HTTP interface.
  2. System fetches collection meta-information from source Milvus (via etcd).
  3. Subscribes to message queue (mq) for data changes.
  4. Processes and forwards changes to the target cluster.
- **Open Source:** Licensed under Apache-2.0. 

## Category
- Data Integration & Migration

## Tags
- milvus
- data-synchronization
- real-time
- vector-databases

## Pricing
Milvus CDC is open source and free to use under the Apache-2.0 license.

## Source
[GitHub Repository](https://github.com/zilliztech/milvus-cdc)