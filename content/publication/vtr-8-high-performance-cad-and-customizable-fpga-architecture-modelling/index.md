---
title: "VTR 8: High-performance CAD and customizable FPGA architecture modelling"
subtitle: Best paper award
publication_types:
  - "2"
authors:
  - Kevin E Murray
  - Oleg Petelin
  - Sheng Zhong
  - Jia Min Wang
  - Mohamed Eldafrawy
  - Jean-Philippe Legault
  - Eugene Sha
  - Aaron G Graham
  - Jean Wu
  - Matthew JP Walker
  - admin
  - Panagiotis Patros
  - Jason Luu
  - Kenneth B Kent
  - Vaughn Betz
publication: ACM Transactions on Reconfigurable Technology and Systems (TRETS)
publication_short: ACM/TRETS
abstract: >-
  Developing Field Programmable Gate Array (FPGA) architectures is challenging
  due to the competing requirements of various application domains, and changing
  manufacturing process technology. This is compounded by the difficulty of
  fairly evaluating FPGA architectural choices, which requires sophisticated
  high-quality Computer Aided Design (CAD) tools to target each potential
  architecture. This article describes version 8.0 of the open source Verilog To
  Routing (VTR) project, which provides such a design flow. VTR 8 expands the
  scope of FPGA architectures which can be modelled, allowing VTR to target and
  model many details of both commercial

  and proposed FPGA architectures. The VTR design flow also serves as a baseline for evaluating new CAD algorithms. It is therefore important, for both CAD algorithm comparisons and the validity of architectural conclusions, that VTR produce high-quality circuit implementations. VTR 8 significantly improves optimization quality (reductions of 15% minimum routable channel width, 41% wirelength, and 12% critical path delay), run-time (5.3× faster) and memory footprint (3.3× lower). Finally, we demonstrate VTR is run-time and memory footprint efficient, while producing circuit implementations of reasonable quality compared to highly-tuned architecture-specific industrial tools – showing that architecture generality, good implementation quality and run-time efficiency are not mutually exclusive goals.
draft: false
featured: false
tags:
  - CAD
  - FPGA
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-06-01T06:10:43.631Z
url_code: https://github.com/verilog-to-routing/vtr-verilog-to-routing
---
