# Trieve

**Category:** Vector Database Engines  
**Tags:** open-source, vector-search, rag, analytics  
**Source:** [GitHub - devflowinc/trieve](https://github.com/devflowinc/trieve)

## Description
Trieve provides an all-in-one infrastructure for vector search, recommendations, retrieval-augmented generation (RAG), and analytics, accessible via API for seamless integration.

## Features
- **Self-Hosting:** Full guides available for deploying in VPC, on-prem, AWS, GCP, Kubernetes, or via Docker Compose.
- **Semantic Dense Vector Search:** Integrates with OpenAI or Jina embedding models and Qdrant for semantic search capabilities.
- **Typo Tolerant Full-Text/Neural Search:** Uses naver/efficient-splade-VI-BT-large-query for typo-tolerant, neural sparse-vector search.
- **Sub-Sentence Highlighting:** Highlights and bolds matching words/sentences in search results for improved UX.
- **Recommendations API:** Find similar content chunks or files, useful for platforms with content interactions (favorite, bookmark, upvote).
- **RAG API Routes:** Integrates with OpenRouter, provides fully-managed RAG with topic-based memory or custom context RAG, and supports any LLM.
- **Bring Your Own Models:** Supports custom text embedding, SPLADE, cross-encoder re-ranking, and LLMs.
- **Hybrid Search:** Combines vector search with cross-encoder re-ranking for improved results (e.g., BAAI/bge-reranker-large).
- **Recency Biasing:** Option to bias search results towards recent content.
- **Tunable Merchandizing:** Adjust search relevance using signals like clicks, add-to-carts, or citations.
- **Filtering:** Supports date-range, substring, tag, numeric, and other filters.
- **Grouping:** Group multiple chunks as part of the same file; search can be performed at file-level to avoid duplicate top-level results.
- **Analytics:** Infrastructure includes analytics components (details not specified in content).
- **Multiple SDKs:** API access via Typescript and Python SDKs.
- **Local Development Support:** Guides and scripts provided for local setup and development.

## Pricing
No explicit pricing details provided in the content. There is mention of Stripe integration for product and plan creation, indicating the possibility of paid plans, but no actual plan details are specified.
