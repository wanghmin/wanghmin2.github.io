---
title: Interactive Two-Way Shape Design of Elastic Bodies
authors:
- Rajaditya Mukherjee
- Longhua Wu
- Huamin Wang
date: '2018-07-01'
publishDate: '2024-03-03T02:42:26.967370Z'
publication_types:
- article-journal
publication: '*Proc. ACM Comput. Graph. Interact. Tech. (I3D)*'
doi: 10.1145/3203196
abstract: We present a novel system for interactive elastic shape design in both forward
  and inverse fashions. Using this system, the user can choose to edit the rest shape
  or the quasistatic shape of an elastic solid, and obtain the other shape that matches
  under the quasistatic equilibrium condition at the same time. The development of
  this system is based on the discovery that inverse quasistatic simulation can be
  immediately solved by Newton's method with a direct solver. To implement our simulator,
  we propose a Jacobian matrix evaluation scheme for the inverse elastic problem and
  we present step length and matrix evaluation techniques that improve the simulation
  performance. While our simulator is efficient, it is still not fast enough for the
  system to generate the result in real time. Our solution is a shape initialization
  method using the recent projective dynamics technique. Shape initialization not
  only works as a fast preview function during the user editing process, but also
  speeds up the convergence of quasistatic or inverse quasistatic simulation afterwards.
  The use of a heterogeneous algorithm structure allows the system to further reduce
  its preview cost, by utilizing the power of both the CPU and the GPU. Our experiment
  demonstrates that the whole system is fast, robust, and convenient for the designer
  to use in both forward and inverse elastic shape design. It can handle a variety
  of nonlinear elastic material models, and its runtime performance has space for
  more improvement.
tags:
- quasistatic simulation
- Newton's method
- inverse elastic problem
- hyperelasticity
- heterogeneous structure
links:
- name: URL
  url: https://doi.org/10.1145/3203196
---
