# usearch

[GitHub Repository](https://github.com/unum-cloud/usearch)

## Description
usearch is a fast, open-source search and clustering engine for similarity search on vectors (and strings in the future), supporting a wide range of programming languages. It is designed to be efficient, compact, and flexible, enabling both approximate and exact search, clustering, and various customizations.

## Features
- **Similarity Search & Clustering**: Supports both approximate (HNSW) and exact (brute-force) similarity search for high-dimensional vectors.
- **Multi-language Support**: Native bindings for C++, C, Python, JavaScript, Rust, Java, Objective-C, Swift, C#, GoLang, and Wolfram.
- **Cross-platform**: Runs on Linux, MacOS, Windows, iOS, Android, WebAssembly, and supports SQLite3 integration.
- **User-defined Metrics**: Allows custom similarity metrics beyond standard inner product and Euclidean distance. Supports custom metrics with Numba, Cppyy, or PeachPy in Python, and similar support in C, C++, and Rust.
- **Efficient Indexing**: Compact codebase, minimal dependencies, and optimized for speed and low memory usage; can handle billions to trillions of entries with efficient storage (32-bit, 40-bit, and 64-bit IDs).
- **Flexible Filtering**: Supports predicate functions for filtering search results during traversal, including integration with external containers (e.g., Bloom filters, third-party databases).
- **Quantization & Memory Efficiency**: Supports automatic up-casting/down-casting between numeric types (f64, f32, f16, i8, b1x8), quantization for RAM savings, and special handling for binary and cosine-like metrics.
- **Serialization & Disk Serving**: Indexes can be saved, loaded, and served from disk, including external memory for cost-efficient deployment.
- **Batch Operations**: Supported in some bindings (notably Python and JavaScript), allowing efficient bulk add/search operations.
- **Joins & Mappings**: Enables approximate, fuzzy, and semantic joins for database and data management use cases.
- **Clustering**: Fast K-Nearest Neighbors clustering and dimensionality reduction (e.g., PCA), often outperforming traditional clustering libraries.
- **Multi-index Lookups**: Supports building and querying multiple indexes in parallel for extremely large-scale workloads.
- **Variable-length Vectors**: Supported in C++.
- **Large-scale Capacity**: Custom 40-bit type for efficient addressing of 4B+ entries.
- **Concurrent Design**: Index structure is concurrent, enabling multi-threaded operations.
- **Application Integrations**: Examples include semantic search (with UForm, UCall), molecular similarity (with RDKit), geospatial search using Haversine distance, and more.
- **Lightweight Deployments**: Minimal dependencies, small binding sizes (e.g., Python binding < 1 MB), and native bindings for low latency.

## Supported Languages and Features Table

| Feature                | C++ | Python | C   | Java | JavaScript | Rust | GoLang | Swift |
|------------------------|-----|--------|-----|------|------------|------|--------|-------|
| Add, search, remove    | ✅   | ✅      | ✅   | ✅    | ✅          | ✅    | ✅      | ✅     |
| Save, load, view       | ✅   | ✅      | ✅   | ✅    | ✅          | ✅    | ✅      | ✅     |
| User-defined metrics   | ✅   | ✅      | ✅   | ❌    | ❌          | ❌    | ❌      | ❌     |
| Batch operations       | ❌   | ✅      | ❌   | ❌    | ✅          | ❌    | ❌      | ❌     |
| Filter predicates      | ✅   | ❌      | ✅   | ❌    | ❌          | ✅    | ❌      | ❌     |
| Joins                  | ✅   | ✅      | ❌   | ❌    | ❌          | ❌    | ❌      | ❌     |
| Variable-length vectors| ✅   | ❌      | ❌   | ❌    | ❌          | ❌    | ❌      | ❌     |
| 4B+ capacities         | ✅   | ❌      | ❌   | ❌    | ❌          | ❌    | ❌      | ❌     |

## Application Examples
- **Semantic Search**: Text-to-image search platforms, multimodal semantic search using encoder models.
- **Molecular Search**: Searching molecular structures using binary fingerprints (e.g., Tanimoto coefficient).
- **Geospatial Search**: GIS applications with Haversine and custom distance functions.

## Licensing
- Open-source

## Pricing
- No pricing information provided; open-source project.
