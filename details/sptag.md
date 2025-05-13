# SPTAG

[Source Code](https://github.com/microsoft/SPTAG)

## Description
SPTAG (Space Partition Tree And Graph) is an open-source, distributed library for approximate nearest neighbor (ANN) search, designed for building and searching large-scale vector indexes efficiently and scalably.

## Features
- **Approximate Nearest Neighbor Search**: Efficiently finds vectors in large datasets that are nearest to a query vector, using L2 or cosine distance metrics.
- **Large-Scale Vector Indexing**: Designed to handle billions of vectors, suitable for big data scenarios.
- **Multiple Indexing Methods**:
  - **SPTAG-KDT**: Uses kd-tree and relative neighborhood graph; advantageous for faster index building.
  - **SPTAG-BKT**: Uses balanced k-means tree and relative neighborhood graph; advantageous for higher search accuracy in high-dimensional data.
- **Distributed Online Serving**: Supports searching across multiple machines for scalability.
- **Online Vector Updates**: Fresh update support allows for online vector insertion and deletion.
- **Index Builder and Searcher Modules**: Modular architecture for index construction and search.
- **Docker Support**: Can be built and run in Docker containers for easy deployment.
- **Language Support**: Core in C++ with Python wrappers available.
- **Open Source and Extensible**: Released under the MIT license, welcoming community contributions.
- **Research-Backed**: Features and algorithms are based on recent research, including support for relaxed monotonicity and incremental in-place updates.

## Requirements
- swig >= 4.0.2
- cmake >= 3.12.0
- boost >= 1.67.0

## Installation
- Supports installation on Linux and Windows, with instructions for both.
- Dockerfile provided for containerized builds.

## Tags
open-source, ann, distributed, scalable

## License
MIT License

## Pricing
SPTAG is open-source and free to use under the MIT license.