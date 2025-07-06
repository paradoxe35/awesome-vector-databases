### AllegroGraph

AllegroGraph is a high-performance, persistent graph database designed for scalability. It utilizes efficient memory and disk-based storage to handle billions of quads while maintaining performance.

#### Features

*   **Scalability:** Scales to billions of quads.
*   **Query Languages:** Supports SPARQL, RDFS++, and Prolog reasoning from numerous client applications.
*   **Reasoning Engine:**
    *   Provides a fast and practical RDFS++ reasoner.
    *   Supports RDF predicates: `RDF:type`, `RDFS:subClassOf`, `range`, `domain`, `subProperty`.
    *   Supports select OWL predicates: `OWL:sameAs`, `inverseOf`, `TransitiveProperty`, `hasValue`, `someValuesFrom`, `allValuesFrom`, `one of`, `equivalentClass`, `restriction`, `onProperty`, `intersectionOf`.
    *   Features Dynamic Materialization for its RDFS++ engine, which dynamically maintains ontological entailments without an explicit materialization phase. This simplifies store maintenance and reduces the time required between data changes and querying.
    *   Includes an OWL2 RL materializer.
*   **Data Loading:** Designed for maximum loading speed with highly optimized RDF/XML and N-Quads parsers.
*   **Resource Management:** Automatically manages all available hardware resources to maximize loading, indexing, and query capabilities.
*   **Database Type:** Described as an OLTP semantic web database.

#### Performance

AllegroGraph is optimized for both loading and query speeds. Historical benchmarks include:

*   First product to load and index 1 billion triples on standard x86 64-bit hardware (2004).
*   Loaded 10 billion quads on Amazon EC2 (2008).

Recent benchmark results demonstrate high loading rates:

*   **1.106 Billion Triples (LUBM(8000)):** 36 min, 49 sec (500,679 T/Sec)
*   **22.12 Billion Triples (LUBM(160,000)):** 12 hrs, 18 min, 16 sec (499,188 T/Sec)
*   **310.269 Billion Triples (Pre-release):** 78 hrs, 9 min, 23 sec (1,102,737 T/Sec)
*   **1.009 Trillion Triples (Pre-release):** 338 hrs, 5 min (829,556 T/Sec)

#### Pricing

Pricing information is not available in the provided content.