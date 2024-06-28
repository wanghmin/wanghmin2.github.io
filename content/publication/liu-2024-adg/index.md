---
title: Automatic Digital Garment Initialization from Sewing Patterns
abstract: The rapid advancement of digital fashion and generative AI technology calls for an automated approach to transform digital sewing patterns into well-fitted garments on human avatars. When given a sewing pattern with its associated sewing relationships, the primary challenge is to establish an initial arrangement of sewing pieces that is free from folding and intersections. This setup enables a physics-based simulator to seamlessly stitch them into a digital garment, avoiding undesirable local minima. To achieve this, we harness AI classification, heuristics, and numerical optimization. This has led to the development of an innovative hybrid system that minimizes the need for user intervention in the initialization of garment pieces. The seeding process of our system involves the training of a classification network for selecting seed pieces, followed by solving an optimization problem to determine their positions and shapes. Subsequently, an iterative selection-arrangement procedure automates the selection of pattern pieces and employs a phased initialization approach to mitigate local minima associated with numerical optimization. Our experiments confirm the reliability, efficiency, and scalability of our system when handling intricate garments with multiple layers and numerous pieces. According to our findings, 68 percent of garments can be initialized with zero user intervention, while the remaining garments can be easily corrected through user operations.
authors:
- Chen Liu
- Weiwei Xu
- Yin Yang
- admin
date: '2024-07-28'
doi: 10.1145/3658128
publishDate: '2024-04-16T07:13:03.080309Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH)*'
summary:
We develop an innovative hybrid system for fast initialization of garment pieces with minimal user intervention, by harnessing AI classification, heuristics, and numerical optimization.
links:
- name: More Video
  url: http://example.org

---
