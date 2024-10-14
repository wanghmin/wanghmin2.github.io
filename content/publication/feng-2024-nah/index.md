---
title: Neural-Assisted Homogenization of Yarn-Level Cloth
authors:
- Xudong Feng
- Huamin Wang
- Yin Yang
- Weiwei Xu
date: '2024-01-01'
publishDate: '2024-10-14T09:55:39.543689Z'
publication_types:
- paper-conference
publication: '*ACM SIGGRAPH 2024 Conference Papers*'
doi: 10.1145/3641519.3657411
abstract: Real-world fabrics, composed of threads and yarns, often display complex
  stress-strain relationships, making their homogenization a challenging task for
  fast simulation by continuum-based models. Consequently, existing homogenized yarn-level
  models frequently struggle with numerical stability without line search at large
  time steps, forcing a trade-off between model accuracy and stability. In this paper,
  we propose a neural-assisted homogenized constitutive model for simulating yarn-level
  cloth. Unlike analytic models, a neural model is advantageous in adapting to complex
  dynamic behaviors, and its inherent smoothness naturally mitigates stability issues.
  We also introduce a sector-based warm-start strategy to accelerate the data collection
  process in homogenization. This model is trained using collected strain energy datasets
  and its accuracy is validated through both qualitative and quantitative experiments.
  Thanks to our model’s stability, our simulator can now achieve two-orders-of-magnitude
  speedups with large time steps compared to previous models.
tags:
- Constitutive Model
- Homogenization
- Neural Networks
- Yarn-level Cloth Simulation
links:
- name: URL
  url: https://doi.org/10.1145/3641519.3657411
---
