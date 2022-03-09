---
title: "GraphSAINT: Graph sampling based inductive learning method"
abstract: "Graph Convolutional Networks (GCNs) are powerful models for learning representations of attributed graphs. To scale GCNs to large graphs, state-of-the-art methods use various layer sampling techniques to alleviate the "neighbor explosion" problem during minibatch training. We propose GraphSAINT, a graph sampling based inductive learning method that improves training efficiency and accuracy in a fundamentally different way. By changing perspective, GraphSAINT constructs minibatches by sampling the training graph, rather than the nodes or edges across GCN layers. Each iteration, a complete GCN is built from the properly sampled subgraph. Thus, we ensure fixed number of well-connected nodes in all layers. We further propose normalization technique to eliminate bias, and sampling algorithms for variance reduction. Importantly, we can decouple the sampling from the forward and backward propagation, and extend GraphSAINT with many architecture variants (e.g., graph attention, jumping connection). GraphSAINT demonstrates superior performance in both accuracy and training time on five large graphs, and achieves new state-of-the-art F1 scores for PPI (0.995) and Reddit (0.970)."
publication_types:
  - "1"
authors:
  - admin
  - Hongkuan Zhou
  - Ajitesh Srivastava
  - Rajgopal Kannan
  - Viktor Prasanna
author_notes:
  - equal contribution
  - equal contribution
publication: International Conference on Learning Representations (ICLR)
publication_short: ICLR
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-05-27T06:52:42.193Z
---
