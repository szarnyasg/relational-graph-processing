# Efficient Graph Processing Using Relational Operators

## Worst-Case Optimal Join (WCOJ) Algorithms and Factorized Query Processing

* `[WCOJ]`: worst-case optimal joins
* `[FACT]`: factorized query processing

## Lectures and Tutorials

* [Lecture by Semih Salihoglu](https://www.youtube.com/watch?v=Hn2XRv8dU5k) at Pinterest Labs (2021) `[WCOJ]` `[FACT]`
* [Lecture by Dan Olteanu](https://www.youtube.com/watch?v=KYgG72oQhOw) (2018) `[WCOJ]` `[FACT]`
* [Lectures series by Dan Olteanu](https://www.youtube.com/watch?v=uaHSAolWTiI&list=PLVjVSqmQgPG_6XsFfv9sTMd5EpWjkfRiX) `[WCOJ]` `[FACT]`
  * [Slides](http://www.cs.ox.ac.uk/dan.olteanu/tutorials/fdb-turing17.pdf)
* SIGMOD 2020 tutorial: [Optimal Join Algorithms Meet Top-k](https://northeastern-datalab.github.io/topk-join-tutorial/) `[WCOJ]`
* [LIquid: Soul of a New Graph Database](https://uwaterloo.ca/data-systems-group/events/dsg-seminar-series-liquid-soul-new-graph-database) by Scott Meyer, presented at the University of Waterloo's DSG Seminar Series
  * [YouTube](https://www.youtube.com/watch?v=wKx-YZn9YQk)

## Papers on worst-case optimal joins

### Theory

* [Worst-Case Optimal Join Algorithms](https://dl.acm.org/doi/10.1145/2213556.2213565) (PODS 2012)
* [Skew Strikes Back: New Developments in the Theory of Join Algorithms](https://arxiv.org/abs/1310.3314) (SIGMOD Record 2013)
* [Worst-Case Optimal Join Algorithms](https://dl.acm.org/doi/10.1145/3180143) (Journal of the ACM 2018)
* [Worst-Case Optimal Graph Joins in Almost No Space](http://aidanhogan.com/docs/wco-ring.pdf) (SIGMOD 2021)
* [Optimizing One-Time and Continuous Subgraph Queries using Worst-Case Optimal Joins](http://amine.io/papers/wco-optimizers-tods21.pdf) (ACM TODS 2021)

### Implementation

* [Distributed Evaluation of Subgraph Queries Using Worst-case Optimal Low-Memory Dataflows](http://www.vldb.org/pvldb/vol11/p691-ammar.pdf) (VLDB 2017)
* [Optimizing subgraph queries by combining binary and worst-case optimal joins](http://www.vldb.org/pvldb/vol12/p1692-mhedhbi.pdf) (VLDB 2019)
* [A Worst-Case Optimal Join Algorithm for SPARQL](http://aidanhogan.com/docs/SPARQL_worst_case_optimal.pdf) (ISWC 2019)
* [Towards Multi-way Join Aware Optimizer in SAP HANA](http://www.vldb.org/pvldb/vol13/p3019-wi.pdf) (VLDB 2020)
* [Adopting Worst-Case Optimal Joins in Relational Database Systems](http://www.vldb.org/pvldb/vol13/p1891-freitag.pdf) in the contest of Umbra (VLDB 2020)
* [GRainDB: A Hybrid Graph-Relational DBMS](https://ldbcouncil.org/event/fourteenth-tuc-meeting/attachments/semih-salihoglu-graindb.pdf) ([recording](https://www.youtube.com/watch?v=FFK3y6vPHJs)) by Semih Salihoglu (LDBC TUC 2021)

## Papers on graph analytics

* [The case against specialized graph analytics engines](http://cidrdb.org/cidr2015/Papers/CIDR15_Paper20.pdf) (CIDR 2015), a paper showing how implementing graph algorithms (SSSP, PageRank, connected components) in T-SQL (Microsoft SQL Server) can outperform the implementations of dedicated graph analytics engines
* [In-database connected component analysis](https://arxiv.org/pdf/1802.09478.pdf) (ICDE 2020), a connected components implementation in SQL

## Papers on data structures and indexing

* [A+ Indexes: Tunable and Space-Efficient Adjacency Lists in Graph Database Management Systems](https://arxiv.org/pdf/2004.00130.pdf) (ICDE 2020)

## Loosely related papers/talks

* [The Relational Data Borg is Learning](http://www.vldb.org/pvldb/vol13/p3502-olteanu.pdf), VLDB 2020 keynote
  * [Slides, part 1](https://fdbresearch.github.io/slides/VLDB2020-keynote1-part1.pdf)
  * [Slides, part 2](https://fdbresearch.github.io/slides/VLDB2020-keynote1-part2.pdf)

## Factorized joins

* [Factorized Databases](https://sigmodrecord.org/publications/sigmodRecord/1606/pdfs/03_principles_Olteanu.pdf) (SIGMOD Record 2016)

## See also

* [Integrating Column-Oriented Storage and Query Processing Techniques Into Graph Database Management Systems](https://arxiv.org/pdf/2103.02284.pdf)
* [Making RDBMSs Efficient on Graph Workloads Through Predefined Joins](https://arxiv.org/pdf/2108.10540.pdf)
