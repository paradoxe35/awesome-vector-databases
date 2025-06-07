# puck

**Source:** [https://github.com/baidu/puck](https://github.com/baidu/puck)

**Category:** open-sources

**Tags:** open-source, vector-search, similarity-search, embedding

---

## Description

Puck is an open-source, high-performance vector search engine designed for fast similarity search and retrieval of embedding vectors. It is intended for large-scale industrial applications where memory constraints, computational resources, and database size are critical factors.

---

## Features

- **Approximate Nearest Neighbor (ANN) Search:** Supports fast and efficient similarity search.
- **Two Algorithms:**
  - **Puck**: Optimized for large-scale datasets, with memory efficiency and high recall-vs-latency performance. Uses a two-layered architectural design for inverted indices and multi-level quantization.
  - **Tinker**: Designed for smaller datasets (e.g., 10M, 100M). Offers better performance than Nmslib in benchmarks but uses more memory than Puck.
- **Written in C++:** Provides Python 3 wrappers for integration with Python projects.
- **Similarity Metrics Supported:**
  - Cosine similarity
  - L2 (Euclidean) distance
  - Inner Product (IP, with transformation to cosine distance)
- **Memory Efficiency:**
  - Puck uses compressed vectors (after product quantization), reducing memory usage to about 1/4 of the original size by default.
  - Tinker requires more memory to store similarity point relationships.
- **Benchmark Results:**
  - Puck demonstrated top performance on multiple 1B-datasets in NeurIPS'21 competition track.
  - Performance improvements since initial release (up to 70% increase).
- **Flexible Configuration:**
  - Configurable via files for training, building, and searching.
  - Supports different vector formats (.fvecs) and raw little endian storage.
- **Build & Deployment:**
  - Requires MKL, Python 3.6+, and CMake 3.21+ for building.
  - Includes demos and tools for training, building, and searching.
- **Benchmark Tools:**
  - Includes scripts and configs for benchmarking against other ANN libraries (e.g., Faiss, Nmslib).

---

## Pricing

Puck is open-source and available for free under its respective license.

---

## Installation & Usage

- Requires Intel MKL, Python 3.6+, CMake 3.21+.
- Build instructions and demos provided in the repository.
- Tools and configs are included for formatting datasets, training, building indices, and performing searches.

---

## Additional Resources

- [Documentation and more details](https://github.com/baidu/puck/blob/main/docs/README.md)
- [Benchmark details](https://github.com/baidu/puck/blob/main/ann-benchmarks/README.md)
