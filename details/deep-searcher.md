# Deep Searcher

**Category**: SDKs & Libraries  
**Tags**: open-source, milvus, langchain, vector-search

## Description
Deep Searcher is a local open-source deep research solution that integrates Milvus (an open-source vector database) and LangChain to provide advanced vector search and retrieval capabilities using open-source models. It is designed as both a Python library and a command-line tool for agentic research workflows.

## Features
- **Agentic RAG (Retrieval-Augmented Generation)**: Automates deep research by decomposing complex queries, searching across multiple document sources, and synthesizing structured reports.
- **Modular Research Pipeline**:
  - **Define/Refine the Question**: Breaks down user queries into sub-queries for more granular research.
  - **Query Routing**: Uses an LLM to route sub-queries to only the most relevant data sources or collections in Milvus.
  - **Similarity Search**: Retrieves relevant document chunks using vector search with Milvus.
  - **Reflection**: The agent reflects on the completeness of its answers, determining if additional sub-queries are needed.
  - **Conditional Execution Flow**: Automatically repeats research steps as needed, based on LLM output, until the research is complete.
  - **Synthesis**: Combines all findings into a consistent and well-structured report.
- **Flexible Data Source Configuration**: Allows input of multiple source documents and manual specification of data sources (local or online).
- **Embedding Model and Vector DB Selection**: Embedding model and vector database can be configured via a configuration file.
- **Web Crawling as a Tool**: Capable of using web crawling for additional data gathering (planned for future updates).
- **Open-Source**: Fully open-source and designed for local or private deployment.
- **Supports Multiple Inference Services**: Works with most inference services, including OpenAI, Gemini, DeepSeek, and Grok 3 (coming soon).
- **Efficient Inference**: Demonstrates use with fast and scalable inference services (e.g., DeepSeek-R1 on SambaNova hardware), but can also run locally with open models.

## Pricing
No pricing information is specified. Deep Searcher is open-source and can be self-hosted. (Inference services such as DeepSeek-R1 may have their own costs.)

## Source
[Deep Searcher Blog Introduction](https://milvus.io/blog/introduce-deepsearcher-a-local-open-source-deep-research.md)
