# Locality-Sensitive Hashing

**Category:** Concepts & Definitions  
**Tags:** ann, similarity-search, high-dimensional, optimization  
**Source:** [Wikipedia - Locality-sensitive hashing](https://en.wikipedia.org/wiki/Locality-sensitive_hashing)

---

## Description
Locality-Sensitive Hashing (LSH) is an algorithmic technique in computer science designed for approximate nearest neighbor search in high-dimensional spaces. It is a form of fuzzy hashing that hashes similar input items into the same "buckets" with high probability, facilitating efficient similarity search and data clustering. Unlike traditional hash functions which minimize collisions, LSH maximizes collisions for similar items, making it especially useful for reducing the dimensionality of data while preserving relative distances.

---

## Features
- **Approximate Nearest Neighbor Search:** Efficiently finds points in high-dimensional spaces that are close to a given query point.
- **Similarity Preservation:** Hashes similar items to the same buckets with high probability, enabling efficient similarity search and clustering.
- **Dimensionality Reduction:** Reduces high-dimensional data to a lower-dimensional representation while maintaining proximity relationships.
- **Flexible Hash Families:** Supports various hash function families for different distance or similarity measures (e.g., Hamming distance, Jaccard index, cosine similarity).
- **Multiple Construction Methods:**
  - *Bit Sampling:* For Hamming distance.
  - *Min-wise Independent Permutations (MinHash):* For Jaccard similarity.
  - *Random Projections (SimHash):* For cosine similarity.
  - *Stable Distributions:* For Lp norms.
  - *Semantic Hashing:* Uses neural networks to learn hash codes with semantic similarity.
- **Amplification Techniques:** Combines multiple hash functions using AND-/OR-constructions to improve selectivity and collision probabilities.
- **Algorithmic Guarantees:** Provides theoretical bounds on preprocessing and query time, space usage, and success probability for approximate nearest neighbor queries.
- **Open Source Implementations:** Notable LSH-based hashes include Nilsimsa (for spam detection) and TLSH (for security and digital forensics), with available open-source code.
- **Scalability:** Suitable for large datasets due to efficient preprocessing and query algorithms with sub-linear or near-linear time complexity.
- **Applications:**
  - Near-duplicate detection
  - Hierarchical clustering
  - Genome-wide association studies
  - Image, audio, and video similarity identification
  - Shared memory and physical data organization in computing
  - Neural network training optimization
  - Computer security and digital forensics
  - Large-scale machine learning

---

## References and Further Reading
- "Mining of Massive Datasets" by Rajaraman, A.; Ullman, J.
- "Similarity Search in High Dimensions via Hashing" by Gionis, A.; Indyk, P.; Motwani, R.
- "Similarity Estimation Techniques from Rounding Algorithms" by Charikar, Moses S.

---

## See Also
- Bloom filter, Feature hashing, Random projection, Principal component analysis

---

## Pricing
*Not applicable (concept/algorithm, not a commercial product).*