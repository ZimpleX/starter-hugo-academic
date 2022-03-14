---
title: Accelerating large scale real-time GNN inference using channel pruning
publication_types:
  - "1"
authors:
  - Hongkuan Zhou
  - Ajitesh Srivastava
  - admin
  - Rajgopal Kannan
  - Viktor Prasanna
doi: https://doi.org/10.14778/3461535.3461547
publication: Proceedings of the VLDB Endowment
publication_short: VLDB
abstract: Graph Neural Networks (GNNs) are proven to be powerful models to
  generate node embedding for downstream applications. However, due to the high
  computation complexity of GNN inference, it is hard to deploy GNNs for
  large-scale or real-time applications. In this paper, we propose to accelerate
  GNN inference by pruning the dimensions in each layer with negligible accuracy
  loss. Our pruning framework uses a novel LASSO regression formulation for GNNs
  to identify feature dimensions (channels) that have high influence on the
  output activation. We identify two inference scenarios and design pruning
  schemes based on their computation and memory usage for each. To further
  reduce the inference complexity, we effectively store and reuse hidden
  features of visited nodes, which significantly reduces the number of
  supporting nodes needed to compute the target embedding. We evaluate the
  proposed method with the node classification problem on five popular datasets
  and a real-time spam detection application. We demonstrate that the pruned GNN
  models greatly reduce computation and memory usage with little accuracy loss.
  For full inference, the proposed method achieves an average of 3.27x speedup
  with only 0.002 drop in F1-Micro on GPU. For batched inference, the proposed
  method achieves an average of 6.67x speedup with only 0.003 drop in F1-Micro
  on CPU. To the best of our knowledge, we are the first to accelerate large
  scale real-time GNN inference through channel pruning.
draft: false
featured: false
tags:
  - GNN
  - model pruning
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-05-10T07:17:55.999Z
---
