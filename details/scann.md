# ScaNN

**ScaNN** (Scalable Nearest Neighbors) is an open-source library developed by Google Research for efficient vector similarity search, particularly designed for large-scale nearest neighbor search applications in AI and machine learning. It is optimized for high-dimensional vector data, such as embeddings generated from text, images, or other modalities.

[Project Source / More Info](https://research.google/blog/announcing-scann-efficient-vector-similarity-search/)

## Features
- **Efficient Approximate Nearest Neighbor Search:** Enables fast similarity search in large datasets of high-dimensional vectors, suitable for millions or billions of items.
- **Anisotropic Vector Quantization:** Implements a novel quantization technique that penalizes error in the direction parallel to the original vector, improving accuracy for maximum inner-product search (MIPS).
- **Optimized for MIPS:** Specifically designed to accelerate maximum inner-product search, a common operation in embedding-based retrieval tasks.
- **High Performance:** Outperforms other vector similarity search libraries on standard benchmarks (e.g., ann-benchmarks.com), achieving up to twice the query throughput for a given accuracy.
- **Open Source:** Available for direct installation via Pip, with source code and documentation on GitHub.
- **Flexible Interfaces:** Supports both TensorFlow and Numpy inputs for easy integration into various machine learning workflows.
- **Scalable:** Handles very large datasets, making it suitable for production-scale AI systems.

## Category
SDKs & Libraries

## Tags
open-source, ann, vector-search, ai

## Pricing
ScaNN is open-source software and is available for free.

## Links
- [Official Blog Announcement](https://research.google/blog/announcing-scann-efficient-vector-similarity-search/)
- [GitHub Repository](https://github.com/google-research/google-research/tree/master/scann)