# OneSparse: A Unified System for Multi-index Vector Search

**Category:** Research Papers & Surveys  
**Tags:** vector-search, performance, scalability, research

## Description
OneSparse is a unified system developed for efficient multi-index vector search, directly addressing performance and scalability challenges in large-scale vector databases. It is particularly relevant for applications such as recommendation systems and search engines that require efficient retrieval from hybrid data sets containing both sparse and dense vectors.

## Features
- **Unified Multi-Vector Index Query System:** Integrates multiple posting-based vector indices to enable efficient retrieval from multi-modal datasets.
- **Novel Query Engine Design:** Introduces inter-index intersection push-down, a technique that allows for more efficient joint searches across multiple indices.
- **Optimized Vector Posting Format:** Enhances the performance of multi-index queries by optimizing how vectors are stored and accessed.
- **Performance Improvement:** Achieves over 6× search performance improvement compared to traditional approaches, while maintaining comparable accuracy.
- **Real-world Deployment:** Integrated into Microsoft online web search and advertising systems, resulting in significant latency reduction (5×+ for Bing web search) and increased revenue metrics (2.0% RPM gain for Bing sponsored search).
- **Supports Hybrid Queries:** Designed for multi-modal queries and multi-model ensemble queries, allowing joint search on multiple vector indices (e.g., sparse and dense vectors).
- **Addresses Limitations of Existing Methods:** Overcomes inefficiencies and algorithmic limitations of isolated search and vector fusion approaches.
- **Efficient Approximate Nearest Neighbor (ANN) Search:** Supports fast and accurate approximate Top-K queries across multiple indices.
- **Minimizes Redundant Computation:** Reduces unnecessary disk I/O and score computation by optimizing intersection and ranking processes.

## Source
[Read the Paper (PDF)](https://www.microsoft.com/en-us/research/wp-content/uploads/2024/04/OneSparse-A-Unified-System-for-Multi-index-Vector-Search.pdf)

## Pricing
Not applicable (research paper).