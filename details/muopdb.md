# MuopDB

[MuopDB GitHub Repository](https://github.com/hicder/muopdb)

MuopDB is an open-source vector database designed for fast and scalable similarity search in AI and machine learning applications.

## Features

- **Vector Database for Machine Learning:** Designed specifically for storing and searching vector embeddings, suitable for AI and LLM "memory" use-cases.
- **Multi-User Support:** Each user can have their own vector index within the same collection, enabling user-specific memory without operational complexity.
- **Efficient Storage:** Indices for all users are stored in a few files, optimizing storage management and reducing complexity.
- **Customizable Collections:** Create collections with configurable parameters such as number of features (dimensions), write-ahead log size, flush interval, and pending operations.
- **Vector Ingestion:** Supports adding vectors to collections, including specifying document and user IDs.
- **Similarity Search:** Perform top-K similarity search queries for given vectors, with options to tune search parameters (e.g., ef_construction).
- **API Access:** Interact with the database via HTTP API, suitable for integration with other tools and services.
- **Open Source:** Released under an open-source license, allowing community contributions and transparency.
- **Docker Support:** Can be run using Docker and Docker Compose for easy deployment.
- **Python and Rust Codebases:** Contains both Python and Rust implementations for flexibility and performance.

## Pricing

MuopDB is open-source software and is available for free.

## Tags

open-source, vector-database, similarity-search, scalable