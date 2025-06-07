# RAFT

[RAFT](https://github.com/rapidsai/raft) is an open-source suite of GPU-accelerated libraries providing fundamental algorithms and primitives for machine learning and information retrieval. It is designed as a C++ header-only template library (with optional shared library), and also offers lightweight Python wrappers (`pylibraft`, `raft-dask`).

## Features

- **CUDA-accelerated primitives** for machine learning and data mining
- **Data Formats**: Support for both sparse and dense data, conversions, and data generation
- **Dense Operations**: Linear algebra, matrix and vector operations, reductions, slicing, norms, factorization, least squares, SVD, and eigenvalue problems
- **Sparse Operations**: Linear algebra, eigenvalue problems, slicing, norms, reductions, factorization, symmetrization, components, and labeling
- **Solvers**: Combinatorial optimization and iterative solvers
- **Statistics**: Sampling, moments and summary statistics, metrics, and model evaluation
- **Tools & Utilities**: Common tools for CUDA application development, multi-node/multi-GPU infrastructure
- **Memory Management**: Integrates with RAPIDS Memory Manager (RMM) for flexible memory allocation strategies
- **Multi-dimensional Arrays**: APIs use `mdspan` for multi-dimensional array views, similar to NumPy's `ndarray`, and provide `mdarray` for memory management on host and device (GPU)
- **Python Bindings**: `pylibraft` and `raft-dask` for Python integration

## Notes

- RAFT is intended for use by developers building high-performance, GPU-accelerated applications, not directly for exploratory data science.
- Some vector search and clustering algorithms have migrated to [cuVS](https://github.com/rapidsai/cuvs), and their RAFT implementations will be deprecated in future releases.

## Pricing

RAFT is open-source software and is available for free under its respective open-source license.