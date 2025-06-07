# NGT

**NGT (Neighborhood Graph and Tree)** is an open-source vector search engine designed for fast and scalable approximate nearest neighbor (ANN) search in high-dimensional data. It provides both command-line tools and a library for performing efficient searches on large datasets.

[GitHub Repository](https://github.com/yahoojapan/NGT)

---

## Features

- **High-speed Approximate Nearest Neighbor Search**: Optimized for high-dimensional vector data (from several tens to several thousands of dimensions).
- **Graph and Tree-based Indexing**: Utilizes neighborhood graphs and tree structures for efficient indexing and retrieval.
- **Scalable to Large Datasets**: Supports indexing and searching on datasets with millions of objects.
- **Shared Memory Support**: Can place the index in shared memory using memory-mapped files, allowing multiple processes to reference the same index and handle indexes too large for memory.
- **Large-scale Data Optimization**: Build options available for improving search time with very large datasets (over 5 million objects).
- **Configurable Build Options**:
  - Enable/disable shared memory allocator
  - Optimize for large datasets
  - Enable/disable quantized graph (QG) and quantized blob graph (QBG) methods (which require BLAS and LAPACK)
- **Multiple Methods Supported**:
  - NGT (graph and tree-based method)
  - QG (quantized graph-based method)
  - QBG (quantized blob graph-based method)
- **Cross-platform Support**: Installation instructions provided for Linux (Ubuntu, CentOS), and macOS (including Homebrew support).
- **Python Support**: Includes a Python interface for integration with Python applications.
- **Benchmark Results**: Publicly available benchmark results (e.g., ann-benchmarks) demonstrating performance on various datasets (GloVe, GIST, Fashion-MNIST, NYTimes, SIFT).

---

## Installation

NGT can be built from source on Linux and macOS, with options to enable/disable specific features. Pre-built binaries are available via Homebrew for macOS.

---

## Supported Programming Languages

- C++ (core library)
- Python (bindings available)

---

## Pricing

NGT is open-source software and is available free of charge under an open-source license.

---

## Tags

`open-source` `vector-search` `ann` `scalable`