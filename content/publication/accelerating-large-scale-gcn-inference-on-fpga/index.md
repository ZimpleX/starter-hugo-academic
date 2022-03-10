---
title: Accelerating large scale GCN inference on FPGA
publication_types:
  - "1"
authors:
  - Bingyi Zhang
  - admin
  - Viktor Prasanna
doi: 10.1109/FCCM48280.2020.00074
publication: 2020 IEEE 28th Annual International Symposium on Field-Programmable
  Custom Computing Machines (FCCM)
publication_short: IEEE/FCCM
abstract: We propose an algorithm-architecture co-optimization framework to
  accelerate large-scale GCN inference on FPGA. We first perform data
  partitioning to fit each partition in the limited on-chip memory of FPGA.
  Then, we use the two-phase pre-processing algorithm consisting of
  sparsification and node reordering. The first phase (sparsification)
  eliminates edge connections of high-degree nodes by merging common neighbor
  nodes. The second phase (re-ordering) effectively groups densely connected
  neighborhoods to improve on-chip data reuse. Incorporating the above
  algorithmic optimizations, we propose an FPGA architecture to efficiently
  execute the two key computational kernels of GCN - feature aggregation and
  weight transformation. We evaluate our design on a state-of-the-art FPGA
  device. Compared with multi-core and GPU baselines, our design reduces the
  inference latency by up to 30x and 2x respectively.
draft: false
featured: false
tags:
  - FPGA
  - GNN
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-05-03T23:52:36.310Z
---
