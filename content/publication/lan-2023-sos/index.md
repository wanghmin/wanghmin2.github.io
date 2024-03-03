---
title: Second-Order Stencil Descent for Interior-Point Hyperelasticity
authors:
- Lei Lan
- Minchen Li
- Chenfanfu Jiang
- Huamin Wang
- Yin Yang
date: '2023-07-01'
publishDate: '2024-03-03T02:42:27.080441Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/3592104
abstract: In this paper, we present a GPU algorithm for finite element hyperelastic
  simulation. We show that the interior-point method, known to be effective for robust
  collision resolution, can be coupled with non-Newton procedures and be massively
  sped up on the GPU. Newton's method has been widely chosen for the interior-point
  family, which fully solves a linear system at each step. After that, the active
  set associated with collision/contact constraints is updated. Mimicking this routine
  using a non-Newton optimization (like gradient descent or ADMM) unfortunately does
  not deliver expected accelerations. This is because the barrier functions employed
  in an interior-point method need to be updated at every iteration to strictly confine
  the search to the feasible region. The associated cost (e.g., per-iteration CCD)
  quickly overweights the benefit brought by the GPU, and a new parallelism modality
  is needed. Our algorithm is inspired by the domain decomposition method and designed
  to move interior-point-related computations to local domains as much as possible.
  We minimize the size of each domain (i.e., a stencil) by restricting it to a single
  element, so as to fully exploit the capacity of modern GPUs. The stencil-level results
  are integrated into a global update using a novel hybrid sweep scheme. Our algorithm
  is locally second-order offering better convergence. It enables simulation acceleration
  of up to two orders over its CPU counterpart. We demonstrate the scalability, robustness,
  efficiency, and quality of our algorithm in a variety of simulation scenarios with
  complex and detailed collision geometries.
tags:
- physics-based simulation
- interior point method
- barrier function
- GPU
links:
- name: URL
  url: https://doi.org/10.1145/3592104
---