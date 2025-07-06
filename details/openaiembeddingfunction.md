# OpenAIEmbeddingFunction

## Description
An embedding function that utilizes the OpenAI API to compute vector embeddings, commonly used with vector databases. This class, part of `pymilvus`, handles encoding text into embeddings using OpenAI models to support embedding retrieval in Milvus.

## Features
The `OpenAIEmbeddingFunction` offers flexible configuration for integrating with OpenAI's embedding services:
- **Model Selection:** Choose from various OpenAI models for encoding, including `text-embedding-3-small`, `text-embedding-3-large`, and `text-embedding-ada-002` (default).
- **API Key Management:** Securely provide your OpenAI API key; the function also checks environment variables as a fallback.
- **Custom Endpoint Support:** Configure a custom base URL for the OpenAI API endpoint, defaulting to the public OpenAI API server.
- **Embedding Dimensions Control:** Specify the desired number of dimensions for the output embeddings, a feature supported by `text-embedding-3` and later models.
- **Extensible Configuration:** Allows passing additional keyword arguments directly to the underlying OpenAI model initialization for advanced use cases.

## Constructor Parameters
To initialize `OpenAIEmbeddingFunction`, the following parameters are available:
- `model_name` (string): Specifies the OpenAI model for encoding. Valid options are `text-embedding-3-small`, `text-embedding-3-large`, and `text-embedding-ada-002` (default).
- `api_key` (string, optional): Your OpenAI API key. If unspecified, environment variables are checked.
- `base_url` (string, optional): The base URL of the OpenAI API endpoint. Defaults to `None` (public OpenAI API server).
- `dimensions` (int, optional): The number of dimensions the resulting output embeddings should have. Only supported in `text-embedding-3` and later models.
- `**kwargs`: Allows additional keyword arguments to be passed to the model initialization.