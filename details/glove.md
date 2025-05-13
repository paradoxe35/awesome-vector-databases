# GloVe

**Category:** SDKs & Libraries  
**Tags:** vector-embeddings, machine-learning, open-source, semantic-search  
**Website:** [https://nlp.stanford.edu/projects/glove/](https://nlp.stanford.edu/projects/glove/)

## Description
GloVe (Global Vectors for Word Representation) is an open-source unsupervised learning algorithm for obtaining vector representations for words. It utilizes global word-word co-occurrence statistics from a corpus to train word vectors that capture semantic and linguistic relationships. These embeddings are widely used in natural language processing tasks, such as semantic search and information retrieval.

## Features
- **Unsupervised word embedding algorithm:** Learns word vectors using aggregated global word-word co-occurrence statistics from large text corpora.
- **Pre-trained word vectors available:** Downloadable vectors trained on major corpora (Wikipedia + Gigaword, Common Crawl, Twitter) in various dimensions (e.g., 25d, 50d, 100d, 200d, 300d).
- **Linear substructure:** Captures semantic relationships and analogies (e.g., king - man + woman ≈ queen) via vector arithmetic.
- **Nearest neighbor queries:** Measures semantic similarity between words using cosine similarity or Euclidean distance.
- **Efficient training:** Populates a co-occurrence matrix in a single pass, with subsequent efficient training iterations.
- **Flexible codebase:** Source code provided (C), with demo scripts and preprocessing tools (including Twitter data scripts).
- **Open-source license:** Code is licensed under Apache License 2.0; pre-trained vectors are released under the Public Domain Dedication and License (PDDL v1.0).
- **Visualization:** Supports visualization of vector space to observe linguistic patterns and frequency effects.
- **Support for large corpora:** Can train on very large datasets (e.g., billions of tokens, millions of vocabulary words).
- **Multi-language support:** While primarily English, can be adapted for other languages with appropriate corpora.
- **Release versions:** Versioned releases with improvements and bug fixes.

## Pricing
- **Free and open source:**
  - Source code: Apache License, Version 2.0
  - Pre-trained vectors: Public Domain Dedication and License v1.0 (PDDL)

## Source
- [GloVe Project Page](https://nlp.stanford.edu/projects/glove/)
- [GitHub Repository](https://github.com/stanfordnlp/GloVe)
