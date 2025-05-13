# Neo4j

**Category:** Vector Database Engines  
**Tags:** graph-database, vector-search, rag, ai

---

## Description
Neo4j is a graph database that now includes vector search capabilities, making it suitable for retrieval augmented generation (RAG) and other AI applications.

---

## Features
- **Graph Database:** Native graph data storage and querying using Cypher.
- **Vector Search Index:** As of v5.13, Neo4j supports a dedicated Vector Search Index.
- **Embedding Storage:** Embeddings can be stored as properties on nodes (e.g., in an "embedding" property).
- **Similarity Metrics:** Supports both Euclidean and Cosine Similarity for vector similarity searches.
- **Cypher Integration:** Vector search and index management are performed via Cypher commands:
  - `db.index.vector.createNodeIndex` for creating vector indexes.
  - `db.create.setNodeVectorProperty` for storing vector data on nodes.
  - `db.index.vector.queryNodes` for querying similar nodes based on vector similarity.
- **Flexible Schema:** Can be adapted for various use cases, such as semantic search in note-taking applications.
- **Top-K Search:** Retrieve top-N similar items ranked by similarity score.

---

## Pricing
No pricing information provided in the available content.

---

## Source
[Neo4j Vector Search - Ken Wagatsuma's Homepage](https://kenwagatsuma.com/blog/neo4j-vector-search)