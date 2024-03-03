---
title: Defending Continuous Collision Detection Against Errors
authors:
- Huamin Wang
date: '2014-07-01'
publishDate: '2024-03-03T02:42:26.871612Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/2601097.2601114
abstract: Numerical errors and rounding errors in continuous collision detection (CCD)
  can easily cause collision detection failures if they are not handled properly.
  A simple and effective approach is to use error tolerances, as shown in many existing
  CCD systems. Unfortunately, finding the optimal tolerance values is a difficult
  problem for users. Larger tolerance values will introduce false positive artifacts,
  while smaller tolerance values may cause collisions to be undetected. The biggest
  issue here is that we do not know whether or when CCD will fail, even though failures
  are extremely rare. In this paper, we demonstrate a set of simple modifications
  to make a basic CCD implementation failure-proof. Using error analysis, we prove
  the safety of this method and we formulate suggested tolerance values to reduce
  false positives. The resulting algorithms are safe, automatic, efficient, and easy
  to implement.
tags:
- continuous collision detection
- floating-point arithmetic
- numerical error
- quadratic and cubic solver
- rounding error
links:
- name: URL
  url: https://doi.org/10.1145/2601097.2601114
---
