# Epsilla

Epsilla is an open-source vector database optimized for high-performance similarity search and scalable storage of vector embeddings. It is designed to be cost-effective and bridges the gap between information retrieval and memory retention in large language models.

## Features
- High performance, production-scale similarity search for embedding vectors
- Full-fledged database management system with familiar concepts (database, table, field); vectors are integrated as a field type
- Metadata filtering capabilities
- Hybrid search combining dense and sparse vectors
- Built-in embedding support for natural language in/out search experiences
- Cloud-native architecture:
  - Compute-storage separation
  - Serverless
  - Multi-tenancy
- Rich ecosystem integrations, including LangChain and LlamaIndex
- Multiple client libraries: Python, JavaScript, Ruby
- REST API interface
- Core written in C++ utilizing advanced parallel graph traversal techniques for vector indexing
  - Achieves up to 10x faster vector search than HNSW
  - Maintains precision levels over 99.9%
- Can be used as a Python library (experimental)

## Pricing
- The open-source Epsilla database is free to use under its open-source license.
- A managed cloud service, Epsilla Cloud (DBaaS), is available. Pricing details are not specified in the provided content.

## Links
- [Source Code & Documentation](https://github.com/epsilla-cloud/vectordb/tree/main)
- [Documentation](https://epsilla-inc.gitbook.io/epsilladb/)
- [Epsilla Cloud](https://cloud.epsilla.com/)