---
title: 'SHARq: sharing recursive queries in relational databases'
authors:
- Lucas C Scabora
- Gabriel Spadon
- Mirela T Cazzolato
- Daniel S Kaster
- Agma JM Traina
- Jose F Rodrigues-Jr
- Caetano Traina-Jr
date: '2021-03-01'
publishDate: '2024-09-15T13:35:34.693827Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 36th Annual ACM Symposium on Applied Computing*'
doi: 10.1145/3412841.3442078
abstract: Processing navigational graph-like queries in relational databases requires
  executing several recursive join operations, which are computationally costly. However,
  when the need for graph-like queries arises, applications often execute a sequence
  of related queries in a single session. We argue that it is possible to reduce the
  total cost of a set of related queries, by expanding individual intermediate results
  and sharing them among multiple queries. SHARq is our framework that enables sharing
  intermediate results of the common graph-like queries Single-Source Shortest Paths
  (SSSP), Connected Components (CC), and PageRank (PR). Our solution prepares result
  tables expanded with additional columns to store partial results of graph-like query
  combinations, such as multiple SSSP, or a sequence of queries comprising SSSP, CC,
  and PR. Experimental results on 9 datasets show query speedups of up to ten times
  when combining multiple SSSP queries, and up to two times when combining SSSP, CC,
  and PR queries. The results reveal a significant reduction in the query time, providing
  timely results for analyses relying on multiple navigational graph-like queries.
tags:
- Recursive Queries
- Relational Databases
- Graph-Like Queries
- Query Optimization
- SHARq
---
