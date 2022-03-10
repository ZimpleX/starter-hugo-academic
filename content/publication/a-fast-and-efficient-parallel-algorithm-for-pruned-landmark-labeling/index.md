---
title: A fast and efficient parallel algorithm for pruned landmark labeling
subtitle: ""
publication_types:
  - "1"
authors:
  - Qing Dong
  - Kartik Lakhotia
  - admin
  - Rajgopal Karman
  - Viktor Prasanna
  - Guna Seetharaman
doi: 10.1109/HPEC.2018.8547548
publication: 2018 IEEE High Performance extreme Computing Conference (HPEC)
publication_short: IEEE/HPEC
abstract: "Hub labeling based shortest distance querying plays a key role in
  many important networked graph applications, such as route planning,
  socially-sensitive search and web page ranking. Over the last few years,
  Pruned Landmark Labeling (PLL) has emerged as the state-of-the-art technique
  for hub labeling. PLL drastically reduces the complexity of label construction
  by pruning Shortest-Path Trees (SPTs). However, PLL is inherently sequential,
  as different SPTs must be constructed in a specific order of source vertices
  to ensure small label size. Particularly, for large graphs, it takes
  significant processing time to construct even pruned SPTs from all vertices in
  the graph. While there are many works on parallelizing single source shortest
  path, these solutions cannot be directly used for PLL, as pruning and label
  querying introduce significant additional complexity while restricting
  parallelism within an SPT. In this paper, we propose a novel, fast and
  efficient algorithm to significantly accelerate PLL on large graphs based on a
  two-level parallelization of SPTs: intra- and inter-tree. For intra-tree, we
  generate pruned SPTs based on a modification of the Bellman-Ford (BF)
  algorithm. We further optimize BF to reduce SPT label querying and
  initialization costs. We implement our algorithm using the recently proposed
  Graph Processing Over Partitions (GPOP) which dramatically improves
  cache-efficiency and DRAM communication-bandwidth. When pruned SPTs become
  very small and parallelizing individual SPTs is not advantageous, we switch to
  inter-tree parallelization and construct multiple trees concurrently in a
  batch. Experiments conducted on a 36 core (2-way hyperthreaded) Intel
  Broadwell server show that on some datasets, our proposed parallel algorithm
  can achieve greater than 35.1× speedup over state-of-the-art sequential
  algorithm."
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-09-25T23:35:38.128Z
---
