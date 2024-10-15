---
title: Volumetric Homogenization for Knitwear Simulation
authors:
- Chun Yuan
- Haoyang Shi
- Lei Lan
- Yuxing Qiu
- Cem Yuksel
- Huamin Wang
- Chenfanfu Jiang
- Kui Wu
- Yin Yang
date: '2024-12-01'
publishDate: '2024-10-14T09:55:39.582190Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH Asia)*'
doi: 10.1145/3687911
abstract: This paper presents volumetric homogenization, a spatially varying homogenization
  scheme for knitwear simulation. We are motivated by the observation that macro-scale
  fabric dynamics is strongly correlated with its underlying knitting patterns. Therefore,
  homogenization towards a single material is less effective when the knitting is
  complex and non-repetitive. Our method tackles this challenge by homogenizing the
  yarn-level material locally at volumetric elements. Assigning a virtual volume of
  a knitting structure enables us to model bending and twisting effects via a simple
  volumepreserving penalty and thus effectively alleviates the material nonlinearity.
  We employ an adjoint Gauss-Newton formulation[Zehnder et al. 2021] to battle the
  dimensionality challenge of such per-element material optimization. This intuitive
  material model makes the forward simulation GPU-friendly. To this end, our pipeline
  also equips a novel domain-decomposed subspace solver crafted for GPU projective
  dynamics, which makes our simulator hundreds of times faster than the yarn-level
  simulator. Experiments validate the capability and effectiveness of volumetric homogenization.
  Our method produces realistic animations of knitwear matching the quality of full-scale
  yarn-level simulations. It is also orders of magnitude faster than existing homogenization
  techniques in both the training and simulation stages.
tags:
- yarn-level simulation
- homogenization
- physics-based simulation
- domain decomposition
links:
- name: URL
  url: https://doi.org/10.1145/3687911
---
