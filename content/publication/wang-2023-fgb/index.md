---
title: Fast GPU-Based Two-Way Continuous Collision Handling
authors:
- Tianyu Wang
- Jiong Chen
- Dongping Li
- Xiaowei Liu
- Huamin Wang
- Kun Zhou
date: '2023-07-01'
publishDate: '2024-03-03T02:42:27.066106Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/3604551
abstract: Step-and-project is a popular method to simulate non-penetrating deformable
  bodies in physically based animation. The strategy is to first integrate the system
  in time without considering contacts and then resolve potential intersections, striking
  a good balance between plausibility and efficiency. However, existing methods can
  be defective and unsafe when using large time steps, taking risks of failure or
  demanding repetitive collision testing and resolving that severely degrade performance.
  In this article, we propose a novel two-way method for fast and reliable continuous
  collision handling. Our method launches an optimization from both ends of the intermediate
  time-integrated state and the previous intersection-free state. It progressively
  generates a piecewise linear path and eventually obtains a feasible solution for
  the next time step. The algorithm efficiently alternates between a forward step
  and a backward step until the result is conditionally converged. Thanks to a set
  of unified volume-based contact constraints, our method offers flexible and reliable
  handling of various codimensional deformable bodies, including volumetric bodies,
  cloth, hair, and sand. Experimental results demonstrate the safety, robustness,
  physical fidelity, and numerical efficiency of our method, making it particularly
  suitable for scenarios involving large deformations or large time steps.
tags:
- nonlinear optimization
- GPU computation
- deformable body simulation
- Collision handling
links:
- name: URL
  url: https://doi.org/10.1145/3604551
---
