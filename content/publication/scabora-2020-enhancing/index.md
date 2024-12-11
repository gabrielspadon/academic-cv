---
title: Enhancing recursive graph querying on RDBMS with data clustering approaches
authors:
- Lucas C. Scabora
- Gabriel Spadon
- Paulo H. Oliveira
- Jose F. Rodrigues-Jr
- Caetano Traina-Jr
date: '2020-03-01'
publishDate: '2024-12-11T19:08:41.662559Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 35th Annual ACM Symposium on Applied Computing*'
doi: 10.1145/3341105.3375770
abstract: Recursive queries are one of the main mechanisms in Relational Database
  Management Systems to process topology-aware, or graph-like, queries. However, existing
  works focus only on optimizing the recursive query statements and processing, disregarding
  the potential physical arrangements that might improve performance. In this work,
  we propose to use an approach based on adjacent-list storage to physically organize
  the graph-like data aiming at both reducing the recursive query time and the number
  of I/O operations. By using Clustered Tables, we tied the adjacency list in chunks
  for (i) storing both vertex and edge tables together in a Combined Tables approach;
  and (ii) reordering the edge table with the Edge Clustered Table approach using
  20% and 80% of the total adjacency list size. The clustered approaches enabled a
  faster recursive query processing (up to 22%) and a reduction of up to 61% in the
  number of page accesses when compared to the Conventional approach. When starting
  from multiple vertices, the Combined Tables approach achieved a query reduction
  time of up to 50% in the first join operation, and Edge Clustered Table 20% provided
  an overall time reduction of up to 20%. The results show that our physical design
  is effective and allows one to use recursive queries without adaptations.
tags:
- Recursive Queries
- Relational Database
- Data Clustering
- Adjacency List Storage
- Query Optimization
---
