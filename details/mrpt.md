# MRPT

MRPT (Multi-Resolution Proximity Trees) is an open-source library for fast approximate nearest neighbor (ANN) search in high-dimensional vector spaces. It is written in C++11 and provides Python bindings. MRPT is designed to be lightweight, easy to use, and efficient, making it suitable for vector database backends and other applications requiring ANN search.

- **Source:** [GitHub Repository](https://github.com/vioshyvo/mrpt)
- **Category:** Open-source
- **Tags:** open-source, ann, high-dimensional, vector-search

## Features
- **Approximate Nearest Neighbor Search:** Efficient ANN search in high-dimensional spaces.
- **C++11 Implementation:** Core library written in modern C++ (header-only).
- **Python Bindings:** Easy integration with Python via pip package (`pip install mrpt`).
- **Random Projection Trees:** Uses a collection of random projection trees to index data for fast querying.
- **Automatic Hyperparameter Tuning:** Integrated autotuning algorithm; only the target recall level and number of neighbors need to be specified. No manual hyperparameter tuning required.
- **Euclidean Distance Metric:** Currently supports Euclidean distance for similarity measurement.
- **Minimal Dependencies:** Only dependency is Eigen (linear algebra library), bundled with the library.
- **No Compilation Required (Header-only):** For C++, just include the header file.
- **Examples Provided:** Minimal usage examples for both Python and C++.
- **Open Source:** MIT license.

## Usage
- **Python:** Install via `pip install mrpt`.
- **C++:** Include the `cpp/Mrpt.h` header and link with Eigen.

## Documentation
- [C++ API documentation](http://vioshyvo.github.io/mrpt/html/index.html)
- [Algorithm description and complexity analysis](https://www.cs.helsinki.fi/u/ttonteri/pub/bigdata2016.pdf)
- [Automatic hyperparameter tuning article](https://arxiv.org/abs/1812.07484)

## Pricing
- **Free and open-source** (MIT License)
