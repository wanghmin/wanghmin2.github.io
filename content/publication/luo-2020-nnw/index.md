---
title: 'NNWarp: Neural Network-Based Nonlinear Deformation'
authors:
- Ran Luo
- Tianjia Shao
- admin
- Weiwei Xu
- Xiang Chen
- Kun Zhou
- Yin Yang
date: '2020-04-01'
publishDate: '2024-11-13T06:03:43.086956Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics, 26*(4)'
doi: 10.1109/TVCG.2018.2881451
abstract: NNWarp is a highly re-usable and efficient neural network (NN) based nonlinear
  deformable simulation framework. Unlike other machine learning applications such
  as image recognition, where different inputs have a uniform and consistent format
  (e.g., an array of all the pixels in an image), the input for deformable simulation
  is quite variable, high-dimensional, and parametrization-unfriendly. Consequently,
  even though the neural network is known for its rich expressivity of nonlinear functions,
  directly using an NN to reconstruct the force-displacement relation for general
  deformable simulation is nearly impossible. NNWarp obviates this difficulty by partially
  restoring the force-displacement relation via warping the nodal displacement simulated
  using a simplistic constitutive model-the linear elasticity. In other words, NNWarp
  yields an incremental displacement fix per mesh node based on a simplified (therefore
  incorrect) simulation result other than synthesizing the unknown displacement directly.
  We introduce a compact yet effective feature vector including geodesic, potential
  and digression to sort training pairs of per-node linear and nonlinear displacement.
  NNWarp is robust under different model shapes and tessellations. With the assistance
  of deformation substructuring, one NN training is able to handle a wide range of
  3D models of various geometries. Thanks to the linear elasticity and its constant
  system matrix, the underlying simulator only needs to perform one pre-factorized
  matrix solve at each time step, which allows NNWarp to simulate large models in
  real time.
summary: We propose NNWarp, a highly re-usable and efficient neural network (NN) based nonlinear
  deformable simulation framework.
tags:
- Artificial neural networks;Deformable models;Strain;Computational modeling;Animation;Elasticity;Neural
  network;machine learning;data-driven animation;nonlinear regression;deformable model;physics-based
  simulation
url_code: https://github.com/lrquad/NNWarp
---
