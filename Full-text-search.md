### Full Text Search: Investigation of Elasticsearch, Solar & Lucene

## Introduction
 I have joined a project  facing some performance and scaling issues, where the team lead asks me to investigate whether using a specialized full-text search engine can improve performance. I explored three widely used technologies  

## Elasticsearch 
 Elasticsearch is a distributed search engine used for fast full-text search. It stores data in an indexed format. It supports features like real-time indexing. It is commonly used in log analysis and monitoring systems.
## solr
 Solr is an open-source enterprise platform built on top of Lucene. It provides powerful full-text search and indexing capabilities through a configurable schema-based approach. It is commonly used in large enterprise systems, e-commerce search, and content-heavy applications.

## Lucene
 Lucene is a low-level library used by both. It provides low-level search features. It is suitable when building a custom search engine. It is fast and reliable.

## Conclusoin
Apache Lucene, Apache Solr, and Elasticsearch are all powerful technologies built for full-text search. Lucene serves as the foundational library, Solr provides an enterprise-grade search platform, and Elasticsearch delivers a modern distributed search engine. 
For systems experiencing performance and scalability issues, Elasticsearch is the most practical and future-proof choice due to its ease of scaling, operational simplicity, and strong real-time capabilities.

## References
- https://www.elastic.co/elasticsearch
- https://solr.apache.org/
- https://lucene.apache.org/
