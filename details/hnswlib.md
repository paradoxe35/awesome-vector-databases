# HNSWLIB

[HNSWLIB](https://github.com/nmslib/hnswlib) is a header-only C++ library with Python bindings for fast approximate nearest neighbor (ANN) search using Hierarchical Navigable Small World (HNSW) graphs. 

## Features

- **Fast Approximate Nearest Neighbor Search:** Implements the HNSW algorithm for efficient high-dimensional vector search.
- **Header-only C++ Implementation:** No dependencies other than C++11.
- **Python Bindings:** Full support for Python with picklable index objects.
- **Incremental Index Construction:** Supports adding, updating, and deleting elements from the index.
- **Multi-threading Support:** Multi-threaded index construction and search; configurable number of threads.
- **Custom Distances:** C++ interface allows user-defined distance functions.
- **Supported Distance Metrics:**
  - Squared L2 ('l2')
  - Inner Product ('ip')
  - Cosine Similarity ('cosine')
- **Filtering Support:** Ability to filter search results by element labels.
- **Efficient Memory Usage:** Lower memory footprint and faster build time compared to some alternatives.
- **Serialization/Deserialization:** Save/load indexes to/from disk; supports pickle in Python.
- **Replace Deleted Elements:** Option to reuse memory of deleted elements.
- **Index Resizing:** Dynamically increase/shrink the index capacity.
- **Multi-vector Document Search and Epsilon Search:** Available in C++ interface.
- **Java and R Support:** External bindings available.
- **Cross-platform:** Usable in C++ and Python environments; external implementations for other languages (Go, Julia, Rust, Java, .NET, etc.).

## Usage Highlights
- Create, initialize, and manage ANN indexes in both C++ and Python.
- Insert, update, delete, and query vectors.
- Batch operations for both insertions and queries.
- Save/load indexes for persistence and scaling.
- Fine-tune speed/accuracy trade-offs with parameters like `ef` and `M`.

## Installation
- Install via pip: `pip install hnswlib`
- Or build from source (see GitHub for details).

## License
- Apache-2.0

## Pricing
- **Open Source:** Free to use under the Apache-2.0 license.

## Resources
- [GitHub Repository](https://github.com/nmslib/hnswlib)
- [Documentation & Examples](https://github.com/nmslib/hnswlib#readme)
- [HNSW Paper](https://ieeexplore.ieee.org/document/8301682)