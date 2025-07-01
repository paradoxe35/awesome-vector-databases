**Hugging Face Tokenizers**
Hugging Face Tokenizers is a library providing fast, state-of-the-art, and versatile tokenizers, optimized for both research and production environments. It implements today's most used tokenizers and is also utilized within the Hugging Face Transformers library.

### Features
*   **Vocabulary Training and Tokenization:** Enables training new vocabularies and performing tokenization using current state-of-the-art tokenizers.
*   **Exceptional Speed:** Achieves extremely fast training and tokenization speeds, powered by its Rust implementation. It can tokenize a gigabyte of text on a server's CPU in less than 20 seconds.
*   **Usability and Versatility:** Designed to be both easy to use and highly versatile for various applications.
*   **Research and Production Ready:** Built to serve both academic research and production deployment needs.
*   **Full Alignment Tracking:** Offers complete alignment tracking, allowing users to retrieve the part of the original sentence corresponding to any token, even after destructive normalization.
*   **Comprehensive Pre-processing:** Handles all necessary pre-processing steps, including truncation, padding, and the addition of special tokens required by models.