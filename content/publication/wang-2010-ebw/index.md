---
title: Example-based wrinkle synthesis for clothing animation
authors:
- Huamin Wang
- Florian Hecht
- Ravi Ramamoorthi
- James F. O'Brien
date: '2010-07-01'
publishDate: '2024-03-01T07:51:40.552052Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
doi: 10.1145/1778765.1778844
abstract: This paper describes a method for animating the appearance of clothing,
  such as pants or a shirt, that fits closely to a figure's body. Compared to flowing
  cloth, such as loose dresses or capes, these types of garments involve nearly continuous
  collision contact and small wrinkles, that can be troublesome for traditional cloth
  simulation methods. Based on the observation that the wrinkles in close-fitting
  clothing behave in a predominantly kinematic fashion, we have developed an example-based
  wrinkle synthesis technique. Our method drives wrinkle generation from the pose
  of the figure's kinematic skeleton. This approach allows high quality clothing wrinkles
  to be combined with a coarse cloth simulation that computes the global and dynamic
  aspects of the clothing motion. While the combined results do not exactly match
  a high-resolution reference simulation, they do capture many of the characteristic
  fine-scale features and wrinkles. Further, the combined system runs at interactive
  rates, making it suitable for applications where high-resolution offline simulations
  would not be a viable option. The wrinkle synthesis method uses a precomputed database
  built by simulating the high-resolution clothing as the articulated figure is moved
  over a range of poses. In principle, the space of poses is exponential in the total
  number of degrees of freedom; however clothing wrinkles are primarily affected by
  the nearest joints, allowing each joint to be processed independently. During synthesis,
  mesh interpolation is used to consider the influence of multiple joints, and combined
  with a coarse simulation to produce the final results at interactive rates.
tags:
- wrinkles
- precomputed animation
- example-based animation
- clothing animation
- cloth simulation
links:
- name: URL
  url: https://doi.org/10.1145/1778765.1778844
---
