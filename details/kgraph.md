# KGraph

KGraph is an open-source library for fast approximate nearest neighbor (ANN) search in high-dimensional vector spaces, with applications in vector database solutions and similarity search.

## Features
- **k-NN Graph Construction:** Builds k-nearest neighbor graphs for datasets.
- **Online k-NN Search:** Supports fast approximate search using the constructed k-NN graph as an index.
- **Heuristic Algorithms:** Implements generic and fast heuristic algorithms for ANN search.
- **C++ API:** Main API is in C++, providing maximum flexibility and performance. Users define custom similarity functions via oracles (callback classes).
- **Python Wrapper:** Provides a Python API (`kgraph`), supporting Euclidean and Angular distances on rows of NumPy matrices.
- **Parameter Tuning:** Both index construction and search support various optional parameters to tune performance.
- **Efficient Oracle Implementations:** Includes oracle implementations for common similarity measures.
- **No Assumptions on Similarity Properties:** Algorithms do not assume properties like the triangle inequality.
- **Installation:** Can be built using CMake or a provided Makefile; Python API installable with `python setup.py install`.
- **Open Source:** Source code available on GitHub under an open-source license.

## Pricing
KGraph is open-source and free to use.

## Links
- [GitHub Repository](https://github.com/aaalgo/kgraph)
- [Doxygen Documentation](http://aaalgo.github.io/kgraph/doc/html/annotated.html)