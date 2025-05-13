# Annoy

[Annoy](https://github.com/spotify/annoy) (Approximate Nearest Neighbors Oh Yeah) is an open-source C++ library with Python bindings for performing approximate nearest neighbor search in high-dimensional spaces. It is optimized for memory usage and supports efficient loading and saving of indexes to disk, enabling large-scale vector search.

## Features

- **Multiple Distance Metrics:** Supports Euclidean, Manhattan, Cosine, Hamming, and Dot (Inner) Product distances.
- **Efficient Memory Usage:** Indexes are designed to be small and can be memory-mapped, allowing multiple processes to share the same data.
- **Index Persistence:** Can create large, read-only file-based data structures that are mmapped into memory, enabling fast loading and sharing.
- **Decoupled Index Creation and Loading:** Indexes can be built once, saved as files, and loaded quickly by many processes.
- **On-Disk Index Building:** Can build indexes directly on disk, making it possible to handle datasets larger than RAM.
- **Cross-Language Bindings:** Native C++ library with Python bindings. Additional community bindings for Go, Lua, Java, Scala, Ruby, Rust, .NET, JVM, and Dart (read-only for some languages).
- **Threaded Index Building:** Supports building indexes using multiple CPU cores.
- **Customizable Parameters:** Number of trees (`n_trees`) and nodes to inspect during searching (`search_k`) can be tuned for trade-offs between speed and accuracy.
- **Static Indexes:** Once built, indexes are read-only (no adding of items after build), promoting immutability and efficiency.
- **Prefaulting Support:** Optionally pre-reads the entire file into memory for faster subsequent searches.
- **Python API:**
  - `AnnoyIndex(f, metric)`: Create index for vectors of dimension `f` with specified metric.
  - `add_item(i, v)`: Add item with integer id `i` and vector `v`.
  - `build(n_trees, n_jobs=-1)`: Build index with specified number of trees and jobs.
  - `save(fn)`, `load(fn)`, `unload()`: Save/load/unload index from disk.
  - `get_nns_by_item(i, n, ...)`, `get_nns_by_vector(v, n, ...)`: Retrieve nearest neighbors.
  - `get_item_vector(i)`, `get_distance(i, j)`, `get_n_items()`, `get_n_trees()`: Various utility functions.
  - `on_disk_build(fn)`: Build index directly on disk.
  - `set_seed(seed)`: Set random seed for reproducible builds.
- **C++ API:** Similar to Python, via `#include "annoylib.h"`.
- **Cross-Platform Support:** Works on Linux, OS X, Windows.
- **Community and Ecosystem:** Widely used in production (e.g., by Spotify for music recommendations), with a large and active community.
- **Open Source:** Licensed under Apache-2.0.

## Pricing

Annoy is open-source software and is free to use under the Apache-2.0 license.

## Resources

- [GitHub Repository](https://github.com/spotify/annoy)
- [PyPI Package](https://pypi.org/project/annoy/)
- [Documentation (README)](https://github.com/spotify/annoy#readme)