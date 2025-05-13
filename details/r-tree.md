# R-tree

**Category:** Concepts & Definitions  
**Tags:** data-structure, spatial-indexing, vector-search, nearest-neighbor

## Description
R-tree is a balanced tree data structure designed for indexing multi-dimensional information such as geographical coordinates, rectangles, or polygons. It supports efficient spatial queries like nearest neighbor and range searches, making it widely used in spatial databases and vector search applications.

## Features
- **Spatial Indexing:** Organizes and indexes multi-dimensional spatial data efficiently.
- **Balanced Tree Structure:** All leaf nodes are at the same depth, similar to B-trees, ensuring balanced search paths.
- **Minimum Bounding Rectangles (MBR):** Groups nearby objects and represents them with their minimum bounding rectangle at higher tree levels.
- **Efficient Queries:** Supports fast spatial queries including range search (find all items within a given area) and nearest neighbor search (find closest items to a point).
- **Filter and Refine Principle:** Uses bounding rectangles to filter out non-relevant branches quickly, then refines the search at the leaf level.
- **Disk-friendly Layout:** Organizes data in pages for efficient storage and retrieval from disk, making it suitable for large datasets.
- **Dynamic Updates:** Supports insertion and deletion of objects, with strategies to minimize overlap and area expansion.
- **Splitting Heuristics:** Employs algorithms such as QuadraticSplit and LinearSplit to split overflowing nodes.
- **Variants:** Includes improved versions like R*-tree (reduces overlap via reinsertion), X-tree (super-nodes for high-dimensional data), and others for specialized performance.
- **Bulk-loading:** Techniques exist to efficiently build R-trees from large datasets.
- **Distributed Support:** Can be implemented in distributed environments using RDMA for scalability and high throughput.
- **Algorithmic Complexity:** Average search time is O(log_M n), where n is the number of objects and M is the max number of entries per node; worst-case search is O(n).
- **Applications:** Used in GIS, map services, clustering algorithms, and any context where spatial queries over large datasets are needed.

## Source
[https://en.wikipedia.org/wiki/R-tree](https://en.wikipedia.org/wiki/R-tree)
