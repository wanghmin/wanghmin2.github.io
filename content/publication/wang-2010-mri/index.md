---
title: Multi-resolution isotropic strain limiting
authors:
- Huamin Wang
- James O'Brien
- Ravi Ramamoorthi
date: '2010-12-01'
publishDate: '2024-03-01T07:51:40.562595Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'
doi: 10.1145/1882261.1866182
abstract: In this paper we describe a fast strain-limiting method that allows stiff,
  incompliant materials to be simulated efficiently. Unlike prior approaches, which
  act on springs or individual strain components, this method acts on the strain tensors
  in a coordinate-invariant fashion allowing isotropic behavior. Our method applies
  to both two-and three-dimensional strains, and only requires computing the singular
  value decomposition of the deformation gradient, either a small 2x2 or 3x3 matrix,
  for each element. We demonstrate its use with triangular and tetrahedral linear-basis
  elements. For triangulated surfaces in three-dimensional space, we also describe
  a complementary edge-angle-limiting method to limit out-of-plane bending. All of
  the limits are enforced through an iterative, non-linear, Gauss-Seidel-like constraint
  procedure. To accelerate convergence, we propose a novel multi-resolution algorithm
  that enforces fitted limits at each level of a non-conforming hierarchy. Compared
  with other constraint-based techniques, our isotropic multi-resolution strain-limiting
  method is straightforward to implement, efficient to use, and applicable to a wide
  range of shell and solid materials.
tags:
- strain limiting
- multi-resolution
- finite element method
links:
- name: URL
  url: https://doi.org/10.1145/1882261.1866182
---
