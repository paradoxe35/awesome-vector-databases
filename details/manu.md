# Manu

**Category:** Vector Database Engines  
**Tags:** vector-databases, cloud-native, vector-search, scalable  
**Source:** [Manu: A Cloud Native Vector Database Management System (VLDB 2022)](https://www.vldb.org/pvldb/vol15/p3548-yan.pdf)

---

## Description
Manu is a cloud-native, scalable vector database management system designed for efficient storage and retrieval of vector embeddings. It is built specifically to address the needs of modern vector data applications, such as recommendation systems, multimedia search, language processing, and more, by focusing on scalability, tunable consistency, elasticity, and high performance.

---

## Features

### Architecture & Design
- **Cloud Native:** Decoupled microservices architecture with four layers: access, coordinator, worker, and storage.
- **Log-based Backbone:** Core communication via write-ahead log (WAL) and binlog services, enabling loose coupling and independent scaling of components.
- **Service-Oriented:** Components (search, indexing, log archiving) can be scaled independently for resource isolation and elasticity.
- **Fine-Grained Decoupling:** Decouples functionalities at the component level (not just read/write), allowing for independent evolution and scaling.
- **Support for Multiple Environments:** Consistent APIs and deployment across personal computers, clusters, and cloud environments (supports S3, MinIO, Linux file system).

### Data Model & Schema
- **Collections:** Analogous to tables, but without inter-collection relations (no joins).
- **Entities:** Support for various data types: vector, string, boolean, integer, float.
- **Primary Key:** Integer or string; auto-generated if not specified.
- **Multiple Labels/Attributes:** Support for multiple labels and numerical attributes per entity, mainly for filtering.
- **Segments and Shards:** Data is partitioned for scalability and efficient storage.

### Consistency & Availability
- **Tunable Consistency:** Delta consistency model allows users to balance between strong and eventual consistency by specifying acceptable data staleness.
- **High Availability:** Component-level failure isolation and transparent failure recovery.

### Performance & Scalability
- **High Performance:** Hardware-aware implementations for CPU, GPU, and SSD.
- **Elasticity:** Fine-grained resource allocation, independent scaling of worker nodes.
- **Optimized for Hardware:** Efficient use of SSDs (bucketed storage for optimal IO), DRAM, and hardware accelerators.
- **Distributed Execution:** Supports billion-scale vector collections, high QPS workloads, and linear scalability with data volume and compute resources.

### Indexing
- **Multiple Index Types:**
  - **Vector Quantization:** PQ, OPQ, RQ, SQ
  - **Inverted Index:** IVF-Flat, IVF-PQ, IVF-SQ, IVF-HNSW, IMI
  - **Proximity Graph:** HNSW, NSG, NGT
  - **Numerical Attribute Indexes:** B-Tree, Sorted List
- **Batch & Stream Indexing:** Supports both offline and online (asynchronous) index building.
- **Automatic Index Parameter Tuning:** Auto-configuration tool using Bayesian Optimization with Hyperband (BOHB).

### Search Capabilities
- **Classical Vector Search:** Supports Euclidean, inner product, and angular distance.
- **Attribute Filtering:** Cost-based strategy selection for efficient attribute-based filtering.
- **Multi-Vector Search:** Supports entities with multiple embedding vectors, with customizable similarity composition.
- **Batch Search:** Option to batch requests for efficiency.
- **Hot Replicas:** Multiple replicas for availability and throughput.

### Usability
- **Multi-language APIs:** Python (PyManu), Java, Go, C++, RESTful API.
- **High-level API:** Simple object-relational mapping for routine operations.
- **GUI Tool (Attu):** Real-time system monitoring, collection/index management, worker node scaling, and search testing.
- **Time Travel:** Point-in-time recovery using checkpoints and log replay.
- **Automatic Data Migration:** Seamless movement between environments with minimal changes.

### Hardware Optimizations
- **SSD-aware Storage:** Efficient bucketed storage and quantization for large-scale vector collections on SSDs.
- **Parallelization:** Tailored for modern multi-core CPUs and GPUs.
- **Minimized Read Amplification:** Column-based binlog format for efficient index building and search.

### Use Cases
- **Recommendation Systems:** E-commerce, music, news, video, social networks.
- **Multimedia Search:** Image, video, audio search and deduplication.
- **Language Applications:** Text search, Q&A, dialogue systems.
- **Security:** Malware/virus scanning via vector similarity.
- **Medicine:** Drug discovery, health risk identification with vectorized chemical/gene data.

---

## Pricing
No pricing information is provided in the available content. Manu is open-sourced and available via [GitHub (Milvus 2.0 branch)](https://github.com/milvus-io/milvus/tree/2.0).

---

## References
- [VLDB 2022 Paper (PDF)](https://www.vldb.org/pvldb/vol15/p3548-yan.pdf)
- [GitHub - Milvus 2.0 (Manu)](https://github.com/milvus-io/milvus/tree/2.0)