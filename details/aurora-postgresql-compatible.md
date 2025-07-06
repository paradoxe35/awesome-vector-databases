### Aurora PostgreSQL-Compatible

Aurora PostgreSQL-Compatible is an AWS database service that provides updates and compatibility with various PostgreSQL engine versions. This includes information on available versions, extensions, and release policies.

#### Supported PostgreSQL Versions

Aurora PostgreSQL supports a range of PostgreSQL versions, including:
*   PostgreSQL 17
*   PostgreSQL 16
*   PostgreSQL 15
*   PostgreSQL 14
*   PostgreSQL 13
*   PostgreSQL 12
*   PostgreSQL 11
*   PostgreSQL 10 (Deprecated)
*   PostgreSQL 9.6 (Deprecated)

#### Features

**PostgreSQL 17.4.2 (Critical Priority Enhancements):**
*   Fixed stuck scaling for serverless DB instances with ZeroETL enabled.
*   Fixed an issue that could cause the database to become unresponsive when performing actions with Aurora storage.

**PostgreSQL 17.4 (New Features):**
*   **Aurora Optimized Reads:** Enables users to resize the allocated space for Optimized Reads-enabled temporary objects on Aurora I/O-Optimized clusters using the dynamic parameter `aurora_temp_space_size`.
*   **Subquery Transformation:** Added support for transforming correlated subqueries into derived tables to improve execution efficiency.

#### Availability

Users can determine which Aurora PostgreSQL DB engine versions are available in an AWS Region by using the `describe-db-engine-versions` AWS CLI command.