# MongoDB Atlas Vector Search

MongoDB Atlas Vector Search is a fully integrated vector search capability within MongoDB Atlas, enabling efficient vector-based retrieval and similarity search over unstructured data such as text, images, and audio. It is designed to power semantic search and generative AI applications directly within the MongoDB database platform.

## Features

- **Native Vector Search in MongoDB Atlas**: Eliminates the need to synchronize data between separate operational and vector databases.
- **Support for Various Data Types**: Handles unstructured data including text, images, and audio by searching over vector embeddings.
- **Hybrid Search Capabilities**: Allows combining vector queries with metadata filters, graph lookups, aggregation pipelines, geo-spatial search, and lexical (text) search in a single query.
- **Scalable Architecture**: Built on MongoDB’s distributed infrastructure, enabling independent scaling of vector search workloads for performance optimization.
- **Enterprise-Ready**: Inherits MongoDB Atlas’s security, high availability, and compliance features.
- **Flexible Vector Embedding Support**: Supports embeddings from any provider, up to 4096 dimensions per vector.
- **Quantization Support**: Ingest, index, and query scalar and binary quantized vectors; supports automatic quantization of full-fidelity vectors.
- **Efficient Search Algorithms**: Implements Approximate Nearest Neighbor (ANN) search using HNSW graphs, as well as Exact Nearest Neighbor (ENN) search for high-precision queries.
- **$vectorSearch Aggregation Stage**: Dedicated aggregation stage for performing vector search with filtering via the MongoDB Query API.
- **Integrated AI Ecosystem**: Integrates with popular frameworks and providers including LangChain, LlamaIndex, OpenAI, Haystack, Microsoft Semantic Kernel, AWS, and Spring.
- **Global Availability**: Available in 125+ regions worldwide as part of MongoDB Atlas.
- **Unified Developer Experience**: Seamless workflow for deploying, managing, and scaling vector search alongside traditional MongoDB workloads.
- **Use Cases**: Semantic search, retrieval-augmented generation (RAG), recommendation engines, anomaly detection, conversational AI, and agentic systems.
- **No Standalone Vector Database Required**: Store and search operational data, metadata, and vector embeddings all in Atlas.

## Pricing

MongoDB Atlas Vector Search is part of the MongoDB Atlas platform. Pricing is based on the underlying Atlas cluster resources (compute, storage, search nodes, etc.) and usage. Detailed and up-to-date pricing information can be found at [https://www.mongodb.com/pricing](https://www.mongodb.com/pricing).

## Links

- [Product page](https://www.mongodb.com/products/platform/atlas-vector-search)
- [Documentation](https://www.mongodb.com/docs/atlas/atlas-vector-search/)
- [Quick Start Guide](https://www.mongodb.com/docs/atlas/atlas-vector-search/tutorials/vector-search-quick-start/)