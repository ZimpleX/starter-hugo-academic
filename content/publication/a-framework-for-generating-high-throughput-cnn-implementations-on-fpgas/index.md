---
title: A framework for generating high throughput CNN implementations on FPGAs
subtitle: Best paper nominee
publication_types:
  - "1"
authors:
  - Hanqing Zeng
  - Ren Chen
  - Chi Zhang
  - Viktor Prasanna
doi: https://doi.org/10.1145/3174243.3174265
publication: Proceedings of the 2018 ACM/SIGDA International Symposium on
  Field-Programmable Gate Arrays
publication_short: ACM/FPGA
abstract: We propose a framework to generate highly efficient accelerators for
  inferencing on FPGAs. Our framework consists of multiple algorithmic
  optimizations for computation complexity and communication volume reduction, a
  mapping methodology for efficient resource utilization, and a tool for
  automatic Verilog generation. The algorithmic optimizations improve throughput
  of frequency domain convolution so as to satisfy a given set of hardware
  constraints. While the Overlap-and-Add (OaA) technique has been known, it
  performs "wasted" computation at the edges. We propose a novel
  Concatenate-and-Pad (CaP) technique, which improves OaA significantly by
  reducing the "wasted" computation on the padded pixels. The proposed CaP used
  in conjunction with OaA enables us to choose a fixed FFT size at design time,
  and achieve low computation complexity for layers with various image sizes and
  kernel window sizes. We also develop a novel frequency domain loop tiling
  technique to further boost throughput by improving data reuse. Our mapping
  methodology optimizes the architecture for the target device by fast design
  space exploration. We quantitatively categorize FPGAs by capturing their DSP
  resources, on-chip memory size and external memory bandwidth into a device
  coefficient. We identify the optimal architectural parameters based on the
  tradeoff between computation and communication cost. Our framework includes a
  tool to automatically generate fully synthesizable Verilog. We demonstrate the
  framework by generating high throughput accelerators for state-of-the-art CNN
  models on Intel HARP heterogeneous platform. Using our framework, we achieve
  throughput of 780.6 GOPS, 669.1 GOPS and 552.1 GOPS for AlexNet, VGG16 and
  FCN-16s respectively. These correspond to 6.8x (AlexNet) and 4.9x (VGG16)
  improvement compared with the state-of-the-art implementations.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-02-15T08:12:30.071Z
---
