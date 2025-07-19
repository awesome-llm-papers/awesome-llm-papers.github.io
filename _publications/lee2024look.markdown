---
layout: publication
title: 'Look Every Frame All At Once: Video-ma\(^2\)mba For Efficient Long-form Video
  Understanding With Multi-axis Gradient Checkpointing'
authors: Lee et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: lee2024look
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.19460'}]
tags: [Attention Mechanism, Tools, CVPR, Transformer, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning]
---
With the growing scale and complexity of video data, efficiently processing
long video sequences poses significant challenges due to the quadratic increase
in memory and computational demands associated with existing transformer-based
Large Multi-modal Models (LMMs). To address these issues, we introduce
Video-Ma\\(^2\\)mba, a novel architecture that incorporates State Space Models
(SSMs) within the Mamba-2 framework, replacing the attention mechanisms. This
allows the LMMs to scale linearly in terms of time and memory requirements,
making it feasible to handle long-duration video content. Furthermore, we
enhance the memory efficiency introducing the Multi-Axis Gradient Checkpointing
(MA-GC) method, which strategically manages memory by retaining only essential
activations across multiple computational axes. Our approach significantly
reduces the memory footprint compared to standard gradient checkpointing.
Empirical analyses show that Video-Ma\\(^2\\)mba can process extensive video
sequences-equivalent to millions of tokens or over two hours of continuous
sequences at 1 FPS-on a single GPU. By maintaining a detailed capture of
temporal dynamics, our model improves the accuracy and relevance of responses
in long video understanding tasks, demonstrating substantial advantages over
existing frameworks.