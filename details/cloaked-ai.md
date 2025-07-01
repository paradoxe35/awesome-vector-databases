# Cloaked AI

Cloaked AI is a product designed for encrypting and decrypting vectors used in AI workflows, which are stored in indices or vector databases. It addresses the need to protect sensitive AI data by allowing vectors to be used for search and related operations even in their encrypted forms.

## Purpose

Vector embeddings, while not exact representations, can capture key facets of original data and often contain sensitive information, necessitating encryption. Traditional encryption methods would render vector similarity searches impossible due to the loss of distance properties. Cloaked AI solves this by enabling data protection while maintaining the usability and functionality of the vectors.

## Features

*   **Vector Encryption**: Encrypts and decrypts vectors for use in AI workflows and storage in vector databases.
*   **Distance-Preserving Encryption**: Utilizes a property-preserving encryption algorithm that maintains the relative distance between vectors. This enables similarity searches (e.g., Euclidean, cosine, or dot product distance) to be performed directly on encrypted data without requiring decryption.
*   **Encrypted Vector Operations**: Allows for vector search and other related operations to function seamlessly with encrypted vectors.
*   **Metadata Encryption**: Offers capabilities for encrypting associated metadata, which may also contain sensitive information.
*   **Standard Metadata Encryption**: For metadata fields that are simply stored and retrieved.
*   **Deterministic Metadata Encryption**: For metadata fields intended for filtering searches, preserving the property of equality.
*   **SDK Integration**: The functionality is accessible through the IronCore Labs Alloy Software Development Kit (SDK), facilitating integration into applications.

## Pricing

Pricing details are not available in the provided content.