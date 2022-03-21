---
abstract: 'State-of-the-art Graph Neural Networks (GNNs) have limited
  scalability with respect to the graph and model sizes. On large graphs,
  increasing the model depth often means exponential expansion of the scope
  (i.e., receptive field). Beyond just a few layers, two fundamental challenges
  emerge: 1. degraded expressivity due to oversmoothing, and 2. expensive
  computation due to neighborhood explosion. We propose a design principle to
  decouple the depth and scope of GNNs -- to generate representation of a target
  entity (i.e., a node or an edge), we first extract a localized subgraph as the
  bounded-size scope, and then apply a GNN of arbitrary depth on top of the
  subgraph. A properly extracted subgraph consists of a small number of critical
  neighbors, while excluding irrelevant ones. The GNN, no matter how deep it is,
  smooths the local neighborhood into informative representation rather than
  oversmoothing the global graph into "white noise". Theoretically, decoupling
  improves the GNN expressive power from the perspectives of graph signal
  processing (GCN), function approximation (GraphSAGE) and topological learning
  (GIN). Empirically, on seven graphs (with up to 110M nodes) and six backbone
  GNN architectures, our design achieves significant accuracy improvement with
  orders of magnitude reduction in computation and hardware cost. '
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Muhan Zhang
  - Yinglong Xia
  - Ajitesh Srivastava
  - Andrey Malevich
  - Rajgopal Kannan
  - Viktor Prasanna
  - Long Jin
  - Ren Chen
summary: >-
  Old GNN models + New data perspective = Surpassing 1-WL, Avoiding
  oversmoothing & Overcoming neighborhood explosion


  * Official code: https://github.com/facebookresearch/shaDow_GNN


  * PyTorch Geometric implementation: https://pytorch-geometric.readthedocs.io/en/latest/modules/loader.html#torch_geometric.loader.ShaDowKHopSampler


  * Deep Graph Library implementation: https://docs.dgl.ai/en/latest/_modules/dgl/dataloading/shadow.html
url_dataset: ""
url_project: "https://github.com/facebookresearch/shaDow_GNN"
author_notes: []
publication_short: NeurIPS
url_source: ""
url_video: ""
publication: Advances in Neural Information Processing Systems (NeurIPS)
featured: true
date: 2021-12-08T07:48:00.000Z
url_slides: "NeurIPS21_slides.pdf"
title: Decoupoling the depth and scope of Graph Neural Networks
subtitle: Deep GNNs on shallow subgraphs
tags:
  - GNN
projects:
  - shaDow-GNN
image:
  caption: "Full shaDow-GNN architecture with subgraph ensemble"
  focal_point: ""
  preview_only: false
publishDate: 2021-12-08T00:00:00.000Z
url_poster: "NeurIPS21_poster.pdf"
url_code: https://github.com/facebookresearch/shaDow_GNN
doi: ""
---
