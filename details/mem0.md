# mem0

mem0 is an open-source vector database focused on efficient storage and retrieval of high-dimensional embeddings for large-scale AI applications. It is designed as an intelligent memory layer for AI, enabling personalized and efficient interactions by retaining user preferences and adapting over time. mem0 is particularly suitable for chatbots and AI-driven tools that require context-aware experiences.

## Features
- **Open-source vector database:** Efficiently stores and retrieves high-dimensional embeddings.
- **Integration with Milvus:** Uses Milvus as the backend vector store for high-performance operations.
- **User memory management:**
  - Add unstructured text as memories, associate with users and metadata.
  - Update existing memories with new information.
  - Retrieve all memories for a user, with filtering options.
  - Track memory update history, including events like add and update.
  - Search memories using similarity search (L2 metric), returning the most relevant entries per user.
  - Delete specific memories by memory ID.
- **Metadata support:** Each memory can include additional metadata for context.
- **History tracking:** Provides a full history of memory changes for auditing and context.
- **Personalization:** Designed to help AI agents remember and adapt to user preferences over time.
- **Python API:** Offers an easy-to-use Python interface for all memory operations.
- **Colab and GitHub Integration:** Ready-to-use tutorials and notebooks for quick experimentation.

## Pricing
No pricing information is provided; mem0 is open-source.

## Links
- [Documentation and Quickstart](https://milvus.io/docs/quickstart_mem0_with_milvus.md)
- [GitHub Repository](https://github.com/milvus-io/bootcamp/blob/master/integration/quickstart_mem0_with_milvus.ipynb)
- [Project Website](https://mem0.ai/)
