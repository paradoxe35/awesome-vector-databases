# MyScale

**Category:** Vector Database Engines  
**Source:** [https://github.com/myscale/myscaledb](https://github.com/myscale/myscaledb)

---

## Description

MyScale is a fork of ClickHouse that extends the original analytical database with high-performance vector search and full-text search capabilities. It is designed to enable scalable and efficient similarity search in combination with SQL queries, making it suitable for building AI and GenAI applications that require both structured and vector data management.

---

## Features

- **SQL-Compatible Vector Database:** Supports standard SQL queries with additional vector-related functions, enabling developers to use familiar SQL syntax for vector operations.
- **Built on ClickHouse:** Inherits OLAP architecture benefits such as columnar storage, advanced compression, skip indexing, and SIMD processing for fast analytics.
- **Efficient Vector Search:** Provides fast, scalable similarity search on large-scale vector data, suitable for billion-scale vectors.
- **Full-Text Search:** Includes high-performance full-text search capabilities and supports text/vector hybrid search queries.
- **Structured & Unstructured Data:** Manages structured data, text, vectors, JSON, geospatial, time-series data, and more within a unified platform.
- **Filtered Search:** Enables high-precision, high-efficiency filtered search by combining vector search with metadata and other attributes.
- **Vector Indexing:** Supports creation of vector indices (e.g., SCANN) with customizable distance metrics (e.g., Cosine).
- **Hybrid Search:** Allows for complex SQL queries that join structured and vector searches, as well as hybrid text and vector search.
- **Observability:** Provides LLM observability tools (MyScale Telemetry) for monitoring large language model workloads.
- **Production-Ready:** Designed for production use with reliability and linear scalability.
- **Open Source:** Available under the Apache-2.0 license.
- **Integration:** Includes Docker images and Docker Compose support for easy deployment. Can be built from source (Ubuntu 22.04 supported).
- **Cloud Service:** MyScale Cloud offers a fully managed version with premium features for billion-scale data, including a free pod for up to 5M 768D vectors.
- **Resource Efficiency:** Consumes fewer resources and provides better performance on joint structured/vector queries compared to alternatives like PostgreSQL with pgvector or ElasticSearch with vector extensions.
- **Extensive Data Type Support:** Handles complex data types, and supports advanced analytics and search functions.

---

## Pricing

- **MyScale Cloud:** Offers a free tier (free pod) supporting up to 5 million vectors of 768 dimensions. Further pricing details are not provided in the available content.

---

## Tags

`vector-search` `sql` `scalable` `hybrid-search`