---
title: Incremental Deformation Subspace Reconstruction
authors:
- R. Mukherjee
- X. Wu
- H. Wang
date: '2016-01-01'
publishDate: '2024-03-03T02:42:26.938077Z'
publication_types:
- article-journal
publication: '*Computer Graphics Forum (Pacific Graphics), 35*(7)'
doi: https://doi.org/10.1111/cgf.13014
abstract: Abstract Recalculating the subspace basis of a deformable body is a mandatory
  procedure for subspace simulation, after the body gets modified by interactive applications.
  However, using linear modal analysis to calculate the basis from scratch is known
  to be computationally expensive. In the paper, we show that the subspace of a modified
  body can be efficiently obtained from the subspace of its original version, if mesh
  changes are small. Our basic idea is to approximate the stiffness matrix by its
  low-frequency component, so we can calculate new linear deformation modes by solving
  an incremental eigenvalue decomposition problem. To further handle nonlinear deformations
  in the subspace, we present a hybrid approach to calculate modal derivatives from
  both new and original linear modes. Finally, we demonstrate that the cubature samples
  trained for the original mesh can be reused in fast reduced force and stiffness
  matrix evaluation, and we explore the use of our techniques in various simulation
  problems. Our experiment shows that the updated subspace basis still allows a simulator
  to generate visual plausible deformation effects. The whole system is efficient
  and it is compatible with other subspace construction approaches.
tags:
- 'I.3.7 Computer Graphics: Three-Dimensional Graphics and Realism—Animation'
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13014
---
