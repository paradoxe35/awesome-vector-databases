# Vector Database

A **vector database** (also known as a vector store or vector search engine) is a specialized type of database designed to store, index, and retrieve data represented as high-dimensional vectors. These databases enable efficient semantic and similarity searches, making them essential for modern applications in AI, machine learning, and information retrieval.

## Features
- **Storage of High-Dimensional Vectors**: Capable of storing fixed-length lists of numbers (vectors) representing data such as text, images, audio, and more.
- **Approximate Nearest Neighbor (ANN) Search**: Implements algorithms to quickly retrieve database records most similar to a given query vector.
- **Semantic and Similarity Search**: Facilitates searching based on meaning or similarity rather than exact matches.
- **Support for Multi-Modal Data**: Can handle vectors derived from diverse data types (text, images, audio, etc.).
- **Integration with Machine Learning**: Feature vectors are often computed using machine learning methods, such as feature extraction, word embeddings, or deep learning networks.
- **Use in Retrieval-Augmented Generation (RAG)**: Supports methods to enhance large language model (LLM) outputs by retrieving relevant context from stored vectors.
- **Recommendation Systems**: Enables building recommendation engines by finding semantically similar items.
- **Techniques for High-Dimensional Search**:
  - Hierarchical Navigable Small World (HNSW) graphs
  - Locality-sensitive Hashing (LSH) and Sketching
  - Product Quantization (PQ)
  - Inverted Files
  - Combinations of these techniques
- **Scalability and Performance**: Designed for efficient search and retrieval in large-scale, high-dimensional datasets.

## Common Use Cases
- Semantic search
- Similarity search
- Multi-modal search
- Recommendation engines
- Long-term memory for large language models (LLMs)
- Object detection
- Retrieval-augmented generation (RAG)

## Implementations
Vector databases can be found as standalone products or as features in broader database systems. Examples include:
- Milvus
- Pinecone
- Weaviate
- Qdrant
- Elasticsearch
- OpenSearch
- MongoDB Atlas
- Redis Stack
- Vespa
- Chroma
- PostgreSQL with pgvector extension
- Many others (see [Wikipedia article](https://en.wikipedia.org/wiki/Vector_database) for a comprehensive list)

## References
- [Wikipedia: Vector database](https://en.wikipedia.org/wiki/Vector_database)

## Category
- Concepts & Definitions

## Tags
- vector-databases
- definition
- semantic-search
- similarity-search