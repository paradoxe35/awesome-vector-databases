# arroy

**Source:** [https://github.com/meilisearch/arroy](https://github.com/meilisearch/arroy)

**Category:** open-sources

**Tags:** open-source, vector-embeddings, similarity-search, vector-search

---

## Description

Arroy is an open-source Rust library for efficient similarity search and management of vector embeddings, designed for use in vector database systems. It provides an interface similar to the Annoy Python library and is optimized for memory usage by leveraging LMDB as its backend storage. This allows multiple processes to share and atomically modify the same data.

---

## Features

- **Approximate Nearest Neighbor (ANN) Search:** Efficiently finds vectors in high-dimensional space that are close to a target vector.
- **Rust Library:** Written in Rust for performance and safety.
- **LMDB Backend:** Utilizes LMDB, a memory-mapped key-value store, allowing concurrent access and modification from multiple processes.
- **Low Memory Footprint:** Designed to handle millions of high-dimensional vectors efficiently.
- **Inspired by Annoy:** Offers a similar API and benefits from low memory usage, with the added advantage of persistent storage.
- **Multi-threaded Access:** The index can be queried by multiple threads or processes simultaneously.
- **Configurable Parameters:**
  - `n_trees`: Number of trees used in the index (affects memory and accuracy).
  - `search_k`: Number of nodes to inspect during a search (affects speed and recall).
  - If `search_k` is not provided, it defaults to `n * n_trees` where `n` is the number of neighbors to search for.
- **Random Projections:** Uses random projection trees for splitting the vector space.
- **Support for High Dimensionality:** Handles vectors with large dimensions (e.g., 768 or 1536).
- **Atomic Modifications:** Safe concurrent updates to the vector index.
- **Open Source:** MIT licensed and available on GitHub and crates.io.

---

## Pricing

Arroy is open-source software, free to use under the MIT license.

---

## Links

- [GitHub Repository](https://github.com/meilisearch/arroy)
- [Documentation](https://docs.rs/arroy)
- [Crates.io](https://crates.io/crates/arroy)