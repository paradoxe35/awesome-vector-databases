# Milvus CLI

Milvus CLI is a command-line interface tool designed for managing and interacting with Milvus vector databases. It allows users to perform a variety of database operations and manage collections efficiently through a set of supported commands.

## Features
- **Connect to Milvus Service:** Supports connecting to Milvus services via URI and authentication details. Allows connection with self-signed certificates for Cloud Pak for Data instances.
- **Database Operations:**
  - Create databases
  - Use/select databases
  - List all databases
- **Collection Management:**
  - Create collections with customizable schema and automatic ID generation
  - Show collection details
  - Delete collections
  - Release collections (unload from memory)
- **Partition Management:**
  - Create partitions within collections
  - Delete partitions
- **Index Management:**
  - Create indexes on fields with support for various index types (e.g., FLAT, IVF_FLAT, IVF_SQ8, HNSW, ANNOY, etc.) and metric types (L2, IP, COSINE, etc.)
  - Show indexes
- **Data Operations:**
  - Insert data into collections (with CSV file support)
  - Load collections (make them available for search/query)
  - Search vectors (vector similarity search and hybrid search with file input)
  - Query collections with expressions
- **Environment:**
  - Runs in a Python environment (requires Python >= 3.8.5)
  - Depends on pymilvus (>=2.5.0) and milvus_cli (>=1.0.2)
- **Command-line Interface:**
  - Interactive CLI with clear command syntax for all supported operations

## Pricing
No pricing information is provided in the available content.

## Source
[Connecting to Milvus Service via Milvus CLI](https://community.ibm.com/community/user/blogs/prabhu-nair/2025/04/17/connecting-to-milvus-service-via-milvus-cli)
