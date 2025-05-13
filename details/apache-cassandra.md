# Apache Cassandra

**Category:** Vector Database Engines  
**Tags:** nosql, distributed, vector-search, scalable  
**Website:** [https://cassandra.apache.org/](https://cassandra.apache.org/)

## Description
Apache Cassandra is an open source, distributed NoSQL database designed for scalability, high availability, and fault tolerance. It is trusted by thousands of companies to manage massive amounts of data without compromising performance. Recent developments include native support for high-dimensional vector storage and approximate nearest neighbor search, making it suitable for AI and vector search workloads.

## Features
- **Open Source:** Licensed under the Apache License 2.0.
- **Distributed, Masterless Architecture:** Every node is identical, with no single points of failure or network bottlenecks.
- **Linear Scalability:** Read and write throughput both increase linearly as new machines are added, with no downtime or interruption.
- **Fault Tolerance:** Supports replication across multiple data centers and can withstand data center outages without data loss.
- **Elasticity:** Data streaming between nodes during scaling operations is up to 5x faster with Zero Copy Streaming, especially useful in cloud and Kubernetes environments.
- **High Performance:** Consistently outperforms other NoSQL alternatives in benchmarks and real applications.
- **Replication Control:** Choice of synchronous or asynchronous replication for each update. Features like Hinted Handoff and Read Repair optimize asynchronous operations.
- **Security and Observability:** Audit logging tracks DML, DDL, and DCL activity; tools like `fqltool` allow for workload analysis.
- **Hybrid Deployment:** Supports public cloud, private cloud, and on-premises deployments.
- **Tested at Scale:** Reliability and stability are ensured by testing on clusters as large as 1,000 nodes and with hundreds of real-world use cases.
- **Vector Search:** Native support for high-dimensional vector storage and approximate nearest neighbor (ANN) search, making it suitable for modern AI workloads.

## Pricing
Apache Cassandra is open source and free to use under the Apache License 2.0.
