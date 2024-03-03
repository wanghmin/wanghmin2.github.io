---
title: Learning-Based Bending Stiffness Parameter Estimation by a Drape Tester
authors:
- Xudong Feng
- Wenchao Huang
- Weiwei Xu
- Huamin Wang
date: '2022-11-01'
publishDate: '2024-03-03T02:42:27.058210Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'
doi: 10.1145/3550454.3555464
abstract: 'Real-world fabrics often possess complicated nonlinear, anisotropic bending
  stiffness properties. Measuring the physical parameters of such properties for physics-based
  simulation is difficult yet unnecessary, due to the persistent existence of numerical
  errors in simulation technology. In this work, we propose to adopt a simulation-in-the-loop
  strategy: instead of measuring the physical parameters, we estimate the simulation
  parameters to minimize the discrepancy between reality and simulation. This strategy
  offers good flexibility in test setups, but the associated optimization problem
  is computationally expensive to solve by numerical methods. Our solution is to train
  a regression-based neural network for inferring bending stiffness parameters, directly
  from drape features captured in the real world. Specifically, we choose the Cusick
  drape test method and treat multiple-view depth images as the feature vector. To
  effectively and efficiently train our network, we develop a highly expressive and
  physically validated bending stiffness model, and we use the traditional cantilever
  test to collect the parameters of this model for 618 real-world fabrics. Given the
  whole parameter data set, we then construct a parameter subspace, generate new samples
  within the sub-space, and finally simulate and augment synthetic data for training
  purposes. The experiment shows that our trained system can replace cantilever tests
  for quick, reliable and effective estimation of simulation-ready parameters. Thanks
  to the use of the system, our simulator can now faithfully simulate bending effects
  comparable to those in the real world.'
tags:
- parameter estimation
- material property acquisition
- deep neural networks
- cloth simulation
- bending stiffness
links:
- name: URL
  url: https://doi.org/10.1145/3550454.3555464
---
