# vearch

**Vearch** is a cloud-native distributed vector database designed for efficient similarity search of embedding vectors in AI applications.

- **Website/Source:** [https://github.com/vearch/vearch](https://github.com/vearch/vearch)
- **Category:** vector-database-engines
- **Tags:** open-source, distributed, vector-search, ai
- **License:** Apache-2.0

## Features

- **Distributed & Cloud-Native:** Built for scalable, distributed deployments.
- **Hybrid Search:** Supports both vector search and scalar filtering.
- **Performance:** Fast vector retrieval, capable of searching millions of objects in milliseconds.
- **Scalability & Reliability:** Supports replication and elastic scaling out.
- **Replication:** Raft-based partition replication for reliability.
- **RESTful APIs:** Provides APIs for upsert, delete, search, and query operations.
- **Multiple SDKs:** Official SDKs for Python and Go; Java SDK under development.
- **Integration with AI Frameworks:**
  - Langchain (Python)
  - LlamaIndex
  - Langchaingo (Go)
  - LangChain4j (Java)
- **Visual Search Support:** Can be used to build large-scale visual search systems (e.g., indexing billions of images).
- **Core Engine:** Uses Gamma, based on Faiss, for vector storage, indexing, and retrieval.
- **Easy Deployment:**
  - Kubernetes (Helm charts)
  - Docker Compose (standalone and cluster modes)
  - Docker and source compilation supported
- **Component Architecture:**
  - **Master:** Schema management, metadata, resource coordination
  - **Router:** REST API, request routing, result merging
  - **PartitionServer (PS):** Hosts document partitions with replication
- **OpenAPI Support:** For API documentation and integration
- **Backup & Compression:** Supports backup with zstd compression
- **Flamegraph UI:** Web UI support for performance flamegraphs

## Pricing

Vearch is open-source and free to use under the Apache-2.0 license. No paid plans are mentioned.

## Usage Examples

- As a memory backend for AI and RAG (retrieval-augmented generation) applications
- As a vector store for frameworks like Langchain and LlamaIndex
- Building large-scale image and visual search systems

## Deployment

- **Kubernetes:** via Helm repository or local charts
- **Docker Compose:** standalone and cluster modes
- **Docker** and **source compilation** options

## References

- [Vearch Documentation](https://github.com/vearch/vearch)
- [API Documentation](https://github.com/vearch/vearch/tree/master/api/openapi)
- [Academic Paper](https://arxiv.org/abs/1908.07389): "The Design and Implementation of a Real Time Visual Search System on JD E-commerce Platform"
