# Milvus Connectors

Milvus Connectors, such as the Spark-Milvus Connector, enable integration between Milvus vector databases and third-party tools like Apache Spark for enhanced machine learning and data processing workflows.

**Source:** [https://github.com/zilliztech/spark-milvus](https://github.com/zilliztech/spark-milvus)

## Features
- **Seamless Integration:** Connects Apache Spark with Milvus, combining Spark's data processing with Milvus's vector storage and query capabilities.
- **Data Formats:**
  - `milvus`: Write Spark DataFrame data into Milvus collections, with automatic collection creation based on the DataFrame schema.
  - `milvusbinlog`: Read Milvus's built-in binlog data (parquet-based, not compatible with standard parquet readers).
  - `mjson`: Generates JSON data in the format required by Milvus's bulk insert feature, improving write performance.
- **Milvus Options:** Configurable connection and management options for Milvus within Spark jobs.
- **MilvusUtils (Scala):** Utility functions to simplify code, including:
  - `readMilvusCollection`: Loads an entire Milvus collection into a Spark DataFrame by wrapping necessary SDK calls and logic.
  - `bulkInsertFromSpark`: Imports Spark output files into Milvus using bulk insert operations.
- **Multi-language Support:** Examples and utilities are available for both Python and Scala.
- **Databricks Integration:** Demos and usage examples for Databricks notebooks.
- **Open Source:** Licensed under the Apache License 2.0.

## Pricing
- The Spark-Milvus Connector is open source and free to use under the Apache License 2.0.

## Category
- Data Integration & Migration

## Tags
- milvus, integration, machine-learning, apache-spark