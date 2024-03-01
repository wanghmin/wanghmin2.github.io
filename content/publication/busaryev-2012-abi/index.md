---
title: Animating bubble interactions in a liquid foam
authors:
- Oleksiy Busaryev
- Tamal K. Dey
- Huamin Wang
- Zhong Ren
date: '2012-07-01'
publishDate: '2024-03-01T07:51:40.599523Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/2185520.2185559
abstract: Bubbles and foams are important features of liquid surface phenomena, but
  they are difficult to animate due to their thin films and complex interactions in
  the real world. In particular, small bubbles (having diameter <1cm) in a dense foam
  are highly affected by surface tension, so their shapes are much less deformable
  compared with larger bubbles. Under this small bubble assumption, we propose a more
  accurate and efficient particle-based algorithm to simulate bubble dynamics and
  interactions. The key component of this algorithm is an approximation of foam geometry,
  by treating bubble particles as the sites of a weighted Voronoi diagram. The connectivity
  information provided by the Voronoi diagram allows us to accurately model various
  interaction effects among bubbles. Using Voronoi cells and weights, we can also
  explicitly address the volume loss issue in foam simulation, which is a common problem
  in previous approaches. Under this framework, we present a set of bubble interaction
  forces to handle miscellaneous foam behaviors, including foam structure under Plateau's
  laws, clusters formed by liquid surface bubbles, bubble-liquid and bubble-solid
  coupling, bursting and coalescing. Our experiment shows that this method can be
  straightforwardly incorporated into existing liquid simulators, and it can efficiently
  generate realistic foam animations, some of which have never been produced in graphics
  before.
tags:
- weighted Voronoi diagram
- surface tension
- natural phenomena
- liquid
- foam
- bubble interaction
links:
- name: URL
  url: https://doi.org/10.1145/2185520.2185559
---
