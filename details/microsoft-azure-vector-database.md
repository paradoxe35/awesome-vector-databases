# Microsoft Azure Vector Database

Microsoft Azure provides vector search capabilities as part of its Azure AI Search service, supporting advanced information retrieval across various content types and scenarios.

## Features
- **Similarity Search**: Retrieve documents by encoding queries and documents into vectors using embedding models (e.g., OpenAI, SBERT).
- **Multimodal Search**: Search across different content types, including text and images, using multimodal embeddings (e.g., OpenAI CLIP, GPT-4 Turbo with Vision).
- **Hybrid Search**: Supports combined vector and keyword search in a single query, merging results for improved relevance.
- **Multilingual Search**: Integrate with embedding and chat models trained in multiple languages; supports multi-language capabilities for both vector and non-vector content.
- **Filtered Vector Search**: Combine vector queries with metadata filters on text or numeric fields.
- **Integration with Azure Services**: Works with Azure AI Foundry, Azure OpenAI (for embeddings), Azure AI Services (image vectorization), and Azure data platforms (Blob Storage, Cosmos DB, SQL, OneLake) for indexing and ingestion.
- **Flexible Embedding Options**: Use Azure OpenAI models, bring your own models, or fine-tune general-purpose models for generating embeddings.
- **Integrated Data Chunking and Vectorization**: Supports both integrated and external vectorization workflows.
- **Vector Store**: Use as a pure vector store for long-term memory, knowledge bases, RAG architectures, and more.
- **Scalable Vector Indexing**: Supports large-scale vector workloads with quotas depending on service tier and creation date.
- **Nearest Neighbor Search Algorithms**:
  - **HNSW (Hierarchical Navigable Small World)**: Optimized for high-recall, low-latency applications; scalable and fast.
  - **Exhaustive K-Nearest Neighbors (KNN)**: Suitable for smaller datasets, finds global nearest neighbors.
- **Approximate Nearest Neighbor (ANN) Search**: Uses HNSW for scalable, efficient retrieval with tunable parameters for recall, latency, and resource usage.
- **Open Source Compatibility**: Commonly used with frameworks like LangChain.

## Pricing
- **Vector search is included at no extra charge** with all Azure AI Search tiers in all regions.
- Newer services (created after April 3, 2024) support higher quotas for vector indexes.

## Category
- Vector Database Engines

## Tags
- cloud-native
- vector-search
- enterprise
- scalable

## Source
[Microsoft Azure Vector Search Overview](https://learn.microsoft.com/en-us/azure/search/vector-search-overview)