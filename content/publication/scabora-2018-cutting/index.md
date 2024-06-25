---
title: 'Cutting-edge Relational Graph Data Management with Edge-k: From One to Multiple
  Edges in the Same Row'
authors:
- L. C. Scabora
- Paulo H. Oliveira
- Gabriel Spadon
- D. S. Kaster
- José F. Rodrigues
- A. Traina
- C. Júnior
date: '2018-06-01'
publishDate: '2024-06-25T18:02:11.082920Z'
publication_types:
- article-journal
publication: '*Journal of Information and Data Management*'
doi: 10.5753/jidm.2018.1634
abstract: Relational Database Management Systems (RDBMSs) are widely employed in several
  applications, including those that deal with data modeled as graphs. Existing solutions
  store every edge in a distinct row in the edge table, however, for most cases, such
  modeling does not provide adequate performance. In this work, we propose Edge-k,
  a technique to group the vertex neighborhood into a reduced number of rows in a
  table through additional columns that stores up to k edges per row. The technique
  provides a better table organization and reduces both table size and query processing
  time. We evaluate Edge-k table management for insert, update, delete and bulkload
  operations, and compare the query processing performance both with the conventional
  edge table — adopted by the existing frameworks — and with the Neo4j graph database.
  Experiments using Single-Source Shortest Path (SSSP) queries reveal that our new
  proposal approach always outperforms the conventional edge table as well as it was
  faster than Neo4j for the first iterations, being slightly slower than Neo4j only
  for iterations after having loaded the whole graph from disk to memory. It was able
  to reach a speedup of 66% over a representative real dataset, with an average reduction
  of up to 58% in our tests. The average speedup over synthetic datasets was up to
  54%. Edge-k was also the best one when performing graph degree distribution queries.
  Moreover, the Edge-k table obtained a processing time reduction of 70% for bulkload
  operations, despite having an overhead of 50% for individual insert, update and
  delete operations. Finally, Edge-k advances the state of the art for graph data
  management within relational database systems.
tags:
- Relational Database Management
- Graph Data Management
- Edge-k
- Query Optimization
- Table Organization
links:
- name: URL
  url: www.semanticscholar.org/paper/bdfd1151a29d5a3219a4ffe907d67f32c4708012
---
