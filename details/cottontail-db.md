# Cottontail DB

**Category:** Vector Database Engines  
**Tags:** open-source, vector-databases, high-dimensional, vector-search

## Description
Cottontail DB is an open-source column store vector database designed for multimedia retrieval. It supports both classical boolean retrieval and vector-space (nearest neighbor) search for similarity queries, utilizing a unified data and query model. The system is intended for use in research and production environments involving high-dimensional data.

## Features
- Column store architecture optimized for multimedia retrieval.
- Support for classical boolean queries.
- Support for vector-space (nearest neighbor) queries for similarity search.
- Unified data and query model for both boolean and vector-space retrieval.
- Communication via gRPC (default port 1865) for easy integration.
- Pre-built stubs and client API available for Kotlin and Java via Maven dependency.
- Command-line interface (CLI) bundled with the distribution; can also be built separately.
- Available as a Docker image from DockerHub for easy deployment.
- Requires Java 11 or newer (OpenJDK or Oracle JDK).
- Gradle-based build system with wrapper included for out-of-the-box setup.
- Compatibility with vitrivr components.
- Comprehensive documentation and example repositories available.

## Pricing
Cottontail DB is open-source software and is freely available under its open-source license.

## Source
[https://github.com/vitrivr/cottontaildb](https://github.com/vitrivr/cottontaildb)