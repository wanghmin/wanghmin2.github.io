---
title: Neural-Assisted Homogenization of Yarn-Level Cloth
abstract: Real-world fabrics, composed of threads and yarns, often display complex stress-strain relationships, making their homogenization a challenging task for fast simulation by continuum-based models. Consequently, existing homogenized yarn-level models frequently struggle with numerical stability without line search at large time steps, forcing a trade-off between model accuracy and stability. In this paper, we propose a neural-assisted homogenized constitutive model for simulating yarn-level cloth. Unlike analytic models, a neural model is advantageous in adapting to complex dynamic behaviors, and its inherent smoothness naturally mitigates stability issues. We also introduce a sector-based warm-start strategy to accelerate the data collection process in homogenization. This model is trained using collected strain energy datasets and its accuracy is validated through both qualitative and quantitative experiments. Thanks to our model’s stability, our simulator can now achieve two-orders-of-magnitude speedups with large time steps compared to previous models.
authors:
- Xudong Feng
- admin
- Yin Yang
- Weiwei Xu
date: '2024-07-28'
publishDate: '2024-04-16T07:13:03.089337Z'
publication_types:
- paper-conference
publication: '*SIGGRAPH 2024 Conference Papers*'
summary: We propose a neural-assisted homogenized constitutive model for simulating yarn-level cloth. This model is trained using collected strain energy datasets and its accuracy is validated through qualitative and quantitative experiments.
tags:
- yarn-level Cloth Simulation
- homogenization
- constitutive Model
- neural Networks
links:
url_video: https://drive.google.com/file/d/1FwcRiS2cNYiT3TCmzf31m4qKQ2Iw36hn/view
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/Ds3pak36tS4?si=pskxfg2dB_yhWdWp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?isOutside=true&aid=112692241105566&bvid=BV1my3pehEgk&cid=500001598444132&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
</p>
