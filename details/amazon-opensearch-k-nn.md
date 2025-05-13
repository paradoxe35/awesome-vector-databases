# Amazon OpenSearch k-NN

**Category:** SDKs & Libraries  
**Tags:** vector-search, ann, managed-service, opensearch

## Description
Amazon OpenSearch's k-NN plugin enables scalable and efficient vector search using approximate nearest neighbor (ANN) algorithms such as IVF and HNSW directly within a managed OpenSearch cluster. This is particularly useful for building, querying, and scaling vector databases on AWS.

[Documentation & Source](https://opensearch.org/docs/latest/search-plugins/knn/)

## Features
- **Vector Search (k-NN):** Implements k-nearest neighbors search to find the closest vectors to a query point in an index.
- **Approximate k-NN (ANN) Algorithms:** Supports efficient, scalable approximate search using algorithms like IVF and HNSW. Offers trade-offs between speed, accuracy, and resource usage.
- **Exact k-NN Search:** Provides brute-force search for exact nearest neighbors, with options for scoring scripts and Painless scripting extensions for custom distance functions.
- **Multiple Distance Functions:** Allows specification of the distance metric (space) for neighbor calculation.
- **Automatic Backend Selection:** Chooses the optimal engine and configuration based on selected mode and available memory.
- **Sparse Vector Search (Neural Sparse Search):** Supports efficient semantic search using sparse embedding models and inverted indexes, with options for automatic embedding generation or direct ingestion.
- **Hybrid Search:** Combines traditional keyword search with vector-based semantic search for improved relevance, using configurable search pipelines that can normalize and combine scores from multiple techniques.
- **Customizable Search Pipelines:** Enables post-filtering, aggregations, and complex query customizations within hybrid search workflows.
- **Integration with AWS Managed OpenSearch:** Directly usable within AWS managed OpenSearch clusters.
- **Optimized for Large and Small Datasets:** ANN methods for large datasets, exact search and custom scoring for smaller or filtered datasets, and flexible scripting for complex use cases.

## Pricing
No pricing information is provided in the source content. For details about costs, refer to AWS OpenSearch managed service pricing.
