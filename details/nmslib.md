# NMSLIB

**NMSLIB (Non-Metric Space Library)** is an efficient and extensible similarity search library and toolkit for high-dimensional vector spaces, with a particular focus on generic and non-metric spaces. It is widely used for approximate nearest neighbor (ANN) search and evaluation of k-NN methods.

- **Website/Source:** [https://github.com/nmslib/nmslib](https://github.com/nmslib/nmslib)
- **License:** Apache-2.0
- **Category:** SDKs & Libraries
- **Tags:** open-source, ANN, similarity-search, high-dimensional

## Features

- **Efficient Similarity Search:** Provides fast search methods in high-dimensional and non-metric spaces.
- **Extensible Architecture:** Supports adding new search methods and distance functions.
- **Multiple Algorithms:** Implements various algorithms for approximate nearest neighbor search, including:
  - Hierarchical Navigable Small World Graphs (HNSW)
  - VP-tree (Vantage Point tree)
  - Neighborhood Approximation index (NAPP)
  - Inverted file based methods
  - k-NN graph construction (NN-Descent)
- **Metric and Non-Metric Spaces:** Principled support for both metric and non-metric space search.
- **Cross-Platform:** Usable on multiple platforms with no third-party dependencies in the core library.
- **Language Support:**
  - Native C++ API
  - Python bindings
  - Query server for Java and other languages via Apache Thrift (Java native client available)
- **Benchmarking Toolkit:** Includes tools to evaluate and benchmark k-NN methods.
- **Standalone HNSW:** Fastest method (HNSW) also available as a header-only standalone library.
- **Open Source:** Actively maintained, with contributions from multiple authors and a strong community.
- **Used in Production:** Integrated into services like Amazon Elasticsearch Service.

## Pricing

NMSLIB is open-source and free to use under the Apache-2.0 license.
