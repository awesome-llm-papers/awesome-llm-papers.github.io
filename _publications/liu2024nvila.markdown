---
layout: publication
title: 'NVILA: Efficient Frontier Visual Language Models'
authors: Liu et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: liu2024nvila
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.04468'}]
tags: [Training Techniques, Attention Mechanism, Evaluation, Model Architecture, Efficiency
    And Optimization, Fine Tuning, Datasets]
---
Visual language models (VLMs) have made significant advances in accuracy in
recent years. However, their efficiency has received much less attention. This
paper introduces NVILA, a family of open VLMs designed to optimize both
efficiency and accuracy. Building on top of VILA, we improve its model
architecture by first scaling up the spatial and temporal resolutions, and then
compressing visual tokens. This "scale-then-compress" approach enables NVILA to
efficiently process high-resolution images and long videos. We also conduct a
systematic investigation to enhance the efficiency of NVILA throughout its
entire lifecycle, from training and fine-tuning to deployment. NVILA matches or
surpasses the accuracy of many leading open and proprietary VLMs across a wide
range of image and video benchmarks. At the same time, it reduces training
costs by 4.5X, fine-tuning memory usage by 3.4X, pre-filling latency by
1.6-2.2X, and decoding latency by 1.2-2.8X. We will soon make our code and
models available to facilitate reproducibility.