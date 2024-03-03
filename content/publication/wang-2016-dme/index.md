---
title: Descent Methods for Elastic Body Simulation on the GPU
authors:
- Huamin Wang
- Yin Yang
date: '2016-12-01'
publishDate: '2024-03-03T02:42:26.945756Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'
doi: 10.1145/2980179.2980236
abstract: We show that many existing elastic body simulation approaches can be interpreted
  as descent methods, under a nonlinear optimization framework derived from implicit
  time integration. The key question is how to find an effective descent direction
  with a low computational cost. Based on this concept, we propose a new gradient
  descent method using Jacobi preconditioning and Chebyshev acceleration. The convergence
  rate of this method is comparable to that of L-BFGS or nonlinear conjugate gradient.
  But unlike other methods, it requires no dot product operation, making it suitable
  for GPU implementation. To further improve its convergence and performance, we develop
  a series of step length adjustment, initialization, and invertible model conversion
  techniques, all of which are compatible with GPU acceleration. Our experiment shows
  that the resulting simulator is simple, fast, scalable, memory-efficient, and robust
  against very large time steps and deformations. It can correctly simulate the deformation
  behaviors of many elastic materials, as long as their energy functions are second-order
  differentiable and their Hessian matrices can be quickly evaluated. For additional
  speedups, the method can also serve as a complement to other techniques, such as
  multi-grid.
tags:
- the Chebyshev method
- nonlinear optimization
- Jacobi preconditioning
- hyperelasticity
- GPU acceleration
links:
- name: URL
  url: https://doi.org/10.1145/2980179.2980236
---
