# Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs

- **Authors:** Yu. A. Malkov, D. A. Yashunin  
- **Category:** Research Paper / Survey  
- **Source:** [arXiv:1603.09320](https://arxiv.org/abs/1603.09320)
- **Tags:** hnsw, ann, vector-search, research

## Description
This paper introduces HNSW (Hierarchical Navigable Small World graphs), a graph-based algorithm for efficient and robust approximate nearest neighbor (ANN) search in high-dimensional spaces. HNSW is widely adopted in vector databases and search engines and is foundational for modern vector search systems.

## Features
- **Graph-Based ANN Search:** HNSW relies entirely on a multi-layer proximity graph structure, eliminating the need for additional coarse search structures.
- **Hierarchical Multi-Layer Design:** Elements are organized in a hierarchy of proximity graphs (layers), supporting nested subsets of the dataset.
- **Randomized Layer Assignment:** Each element's highest layer is chosen randomly with an exponentially decaying probability, leading to efficient, scale-separated graph construction.
- **Logarithmic Complexity:** Starting the search at the upper layers and utilizing scale separation enables logarithmic scaling of search complexity.
- **Heuristic Neighbor Selection:** Employs a heuristic for selecting neighbors in the proximity graph, improving performance at high recall and with highly clustered data.
- **Superior Performance:** Demonstrated to outperform previous open-source state-of-the-art vector-only approaches for ANN search in general metric spaces.
- **Distributed Implementation:** The structural similarity to skip lists allows for straightforward, balanced, distributed implementations.

## References
- [Paper on arXiv](https://arxiv.org/abs/1603.09320)

## Pricing
N/A (Research paper)
