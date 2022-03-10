---
title: "DecGNN: a framework for mapping decoupled GNN models onto CPU-FPGA
  heterogeneous platform"
publication_types:
  - "1"
authors:
  - Bingyi Zhang
  - admin
  - Viktor Prasanna
doi: https://doi.org/10.1145/3490422.3502326
publication: Proceedings of the 2022 ACM/SIGDA International Symposium on
  Field-Programmable Gate Arrays
publication_short: ACM/FPGA (poster)
abstract: "A well-known issue in mini-batch GNN inference is neighborhood
  explosion. This results in two challenges for its hardware acceleration: (1)
  high computation and communication costs resulting in high latency, and (2)
  low computation-to-communication ratio leading to low hardware utilization. To
  address these challenges, we propose a hardware mapping framework following
  the recently proposed GNN design principle of model depth-receptive field
  decoupling. We show that Decoupled GNNs enjoy significantly higher
  computation-to-communication ratio, therefore, are more suitable for hardware
  acceleration. To efficiently map Decoupled GNNs onto CPU-FPGA heterogeneous
  platforms, we propose the following model-architecture co-optimizations: (1)
  Model instantiation: according to the bandwidth and computation resources, we
  determine the number of GNN layers to achieve high hardware utilization; (2)
  Neighbor selection: to meet the application constraint, we select a small
  number of important neighbors surrounding the target vertices to improve the
  throughput without sacrificing accuracy; (3) Hardware mapping: given the model
  and neighborhood defined above, we determine the accelerator parameters based
  on our novel hardware templates, enabling fast computation of GNN inference
  workloads. We evaluate our framework on two state-of-the-art FPGA platforms,
  using two models (GCN, GraphSAGE). Experiments show that the resulting designs
  achieve high hardware utilization 88%-94% and significant speedup (1.1x-2.5x)
  compared with the implementations on state-of-the-art CPU-GPU platform."
draft: false
featured: false
tags:
  - FPGA
  - GNN
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-02-14T00:56:44.855Z
---
