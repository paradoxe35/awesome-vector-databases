# Vector Transport Service (VTS)

[Source](https://zilliz.com/vector-transport-service)

**Category:** Data Integration & Migration  
**Tags:** vector-data, migration, integration, milvus

## Description
Vector Transport Service (VTS) is an open-source, self-hosted toolkit designed for secure and efficient migration and synchronization of vector and unstructured data between various data platforms. It supports large-scale data movement, including schema mapping and format conversion, and can operate entirely within private infrastructure.

## Features
- **Open-source & Self-hosted**: Deploy VTS in your own environment (Docker or Kubernetes), maintaining full control over the code and data pipeline.
- **Private Infrastructure Support**: No public internet access required; migrate data securely between on-premises databases or air-gapped networks.
- **Broad Data Source Compatibility**: Supports migration from and to Milvus, Zilliz Cloud, Elasticsearch, Pinecone, Qdrant, PostgreSQL, and others, across both cloud and on-premises environments.
- **Flexible Deployment**: Can be installed and managed on Docker or Kubernetes.
- **Custom Data Transformation**: Apply schema mappings or embedding conversions during migration, handling schema conflicts, format conversions, and version control for vector data.
- **Batch and Real-time Migration**: Supports both one-time batch migrations and continuous synchronization (real-time sync with manual configuration).
- **Scalable and High Performance**: Designed for large-scale, high-speed data transfers without compromising reliability.
- **Enterprise-ready**: Allows for custom transformations, streaming or batch modes, and scalable operations via Kubernetes.
- **No Pipeline Rebuild Required**: Handles format and schema changes without needing to rebuild data pipelines from scratch.

## Pricing
- **Free**: VTS is open-source and free to use. Users are responsible for their own infrastructure and operational costs (self-hosted, user-managed).

## Additional Notes
- VTS is suitable for organizations needing full control over their data migration processes and operating in secure or private environments.
- For a fully managed, out-of-the-box solution with enterprise support, Zilliz offers the Zilliz Migration Service, which is built on top of VTS.