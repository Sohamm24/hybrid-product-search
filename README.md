# Hybrid Product Search — Production-Grade Engine

A high-throughput, low-latency **hybrid product search engine** built for **Quick Commerce** catalogs. It combines **lexical** and **semantic** retrieval to deliver accurate results across **Hinglish** and **typo-prone** user queries.

## Key Capabilities

- **Sub-Second Latency at Scale**: Optimized to search **33K+ Quick Commerce products** within sub-second response times.
- **High Throughput**: Architected to handle up to **1 lakh (100,000) searches per second**.
- **Hinglish & Typo-Tolerant Queries**: Handles transliterated Hinglish terms, phonetic variations, and common spelling mistakes seamlessly.
- **Lexical + Semantic Hybrid Search**: Blends exact/fuzzy keyword matching with dense semantic similarity for strong recall and relevance.

## Architecture Overview

1. **Query Processing**: Normalizes incoming queries, handles Hinglish variations, and applies typo tolerance.
2. **Hybrid Retrieval**:
   - **Lexical Search**: Captures exact SKU/brand/product matches and fuzzy keyword hits.
   - **Semantic Search**: Captures user intent and conceptual similarity beyond exact keywords.
3. **Fusion & Ranking**: Combines lexical and semantic signals to return the most relevant products with sub-second latency.
