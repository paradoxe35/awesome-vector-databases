# SentenceTransformer

## Description
Sentence Transformers (a.k.a. SBERT) is a Python module for accessing, using, and training state-of-the-art embedding and reranker models. It can be used to compute embeddings using Sentence Transformer models or to calculate similarity scores using Cross-Encoder (reranker) models. This unlocks a wide range of applications.

## Features
*   **Model Capabilities:**
    *   Compute embeddings with Sentence Transformer models.
    *   Calculate similarity scores with Cross-Encoder (reranker) models.
*   **Applications:**
    *   Semantic search
    *   Semantic textual similarity
    *   Paraphrase mining
*   **Model Availability & Customization:**
    *   Access to over 10,000 pre-trained Sentence Transformers models are available on Hugging Face.
    *   Ability to train or finetune custom embedding models.
    *   Ability to train or finetune custom reranker models.
*   **API & Utilities:**
    *   Includes a new training API for CrossEncoder (reranker) models (introduced in v4.0).
    *   Supports ONNX and OpenVINO backends for CrossEncoder models to speed up inference (introduced in v4.1).
    *   Provides functions for:
        *   Quantizing embeddings: `quantize_embeddings()`
        *   Semantic search: `semantic_search()`, `semantic_search_faiss()`, `semantic_search_usearch()`
        *   Community detection: `community_detection()`
        *   Mining hard negatives: `mine_hard_negatives()`
        *   Normalizing embeddings: `normalize_embeddings()`
        *   Paraphrase mining: `paraphrase_mining()`
        *   Truncating embeddings: `truncate_embeddings()`
        *   Exporting models: `export_dynamic_quantized_onnx_model()`, `export_optimized_onnx_model()`, `export_static_quantized_openvino_model()`
        *   Similarity metrics: `cos_sim()`, `dot_score()`, `euclidean_sim()`, `manhattan_sim()`, `pairwise_cos_sim()`, `pairwise_dot_score()`, `pairwise_euclidean_sim()`, `pairwise_manhattan_sim()`

## Installation
*   Install using pip.
*   Requires Python 3.9+ and PyTorch 1.11.0+.