---
title: 'Make Fashion Real: Texture-preserving Rendered-to-Real Translation with Diffusion
  Models'
authors:
- Rui Hu
- Qian He
- Jiedong Zhuang
- Huang Chen
- Huafeng Liu
- admin
date: '2024-12-10'
publishDate: '2024-10-14T09:55:39.590352Z'
publication_types:
- paper-conference
publication: '*ACM Trans. Graph. (SIGGRAPH), 39*(3)'
doi: 10.1145/3384515
abstract: We propose a framework for the interactive simulation of nonlinear deformable
  objects. The primary feature of our system is the seamless integration of deformable
  simulation and collision culling, which are often independently handled in existing
  animation systems. The bridge connecting them is the medial axis transform (MAT),
  a high-fidelity volumetric approximation of complex 3D shapes. From the physics
  simulation perspective, MAT leads to an expressive and compact reduced nonlinear
  model. We employ a semireduced projective dynamics formulation, which well captures
  high-frequency local deformations of high-resolution models while retaining a low
  computation cost. Our key observation is that the most compelling (nonlinear) deformable
  effects are enabled by the local constraints projection, which should not be aggressively
  reduced, and only apply model reduction at the global stage. From the collision
  detection (CD)/collision culling (CC) perspective, MAT is geometrically versatile
  using linear-interpolated spheres (i.e., the so-called medial primitives (MPs))
  to approximate the boundary of the input model. The intersection test between two
  MPs is formulated as a quadratically constrained quadratic program problem. We give
  an algorithm to solve this problem exactly, which returns the deepest penetration
  between a pair of intersecting MPs. When coupled with spatial hashing, collision
  (including self-collision) can be efficiently identified on the GPU within a few
  milliseconds even for massive simulations. We have tested our system on a variety
  of geometrically complex and high-resolution deformable objects, and our system
  produces convincing animations with all of the collisions/self-collisions well handled
  at an interactive rate.
summary: We introduce a novel diffusion-based framework that effectively translates rendered
images into realistic counterparts, ensuring the preservation of texture details. 
---
