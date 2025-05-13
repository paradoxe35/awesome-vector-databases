# Microsoft Azure AI Search

**Category:** Vector Database Engines  
**Tags:** managed-service, vector-search, hybrid-search, cloud-native

[Learn more](https://learn.microsoft.com/en-us/azure/search/search-api-preview)

## Description
Azure AI Search is a managed service providing advanced search capabilities, including vector search (approximate KNN), hybrid search, and deep integration with other Azure AI tools and services. It is designed to handle complex search scenarios combining traditional keyword search with AI-driven semantic and vector-based retrieval.

## Features
- **Vector Search**: Supports approximate k-nearest neighbor (KNN) search and hybrid search combining vector and keyword queries.
- **Preview Features**: Includes frequent updates and preview access to advanced features via REST API.
- **Semantic Ranking**: Semantic search and reranking using advanced AI models, with options for query rewriting and semantic reranking.
- **Vector Rescoring**: Rescore vector queries using full-precision vectors, and options for rescoring compressed vectors.
- **Facet Hierarchies & Aggregations**: Nested facet support, numeric aggregations, and facet-level filters.
- **Document Layout and Text Split Skills**: Built-in skills for analyzing document structure and chunking text for embeddings.
- **Multimodal Embedding**: Generate embeddings for text and images using Azure AI Vision.
- **Integration with Azure AI and Machine Learning**: Use managed identity for AI skills, integrate with Azure Machine Learning endpoints and models, and connect to Azure AI Foundry model catalog.
- **Indexers for Multiple Data Sources**: Index data from Azure Blob Storage (with soft delete recognition), Azure Files, SharePoint Online, MySQL, Azure Cosmos DB (MongoDB, Gremlin APIs), OneLake, and more.
- **Markdown Parsing**: Indexers can parse and index Markdown files.
- **Incremental Enrichment Cache**: Caching for enriched documents to optimize updates.
- **Advanced Query Capabilities**: Query rewrite, spelling correction, normalizers for text preprocessing, moreLikeThis queries, and document reset.
- **Hybrid Search Customization**: Fine-grained control over hybrid search, such as filtering, recall size, and subscore unpacking for debugging.
- **Security**: Support for network security perimeter and user-assigned managed identities.
- **Service Management**: Upgrade service storage limits, change pricing tiers, and manage via REST API.
- **SDK Support**: Beta features and updates are available in Azure SDKs for .NET, Java, JavaScript, and Python.

## Pricing
- **Pricing Tiers**: Multiple pricing tiers are available (Basic and Standard S1, S2, S3), with the ability to change tiers for scaling storage, throughput, and latency needs.
- **Details**: For full pricing details, refer to the [official Azure AI Search pricing page](https://azure.microsoft.com/en-us/pricing/details/search/).

## Source
- [Microsoft Docs: Azure AI Search Preview Features](https://learn.microsoft.com/en-us/azure/search/search-api-preview)