---
layout: publication
title: Region-adaptive Sampling For Diffusion Transformers
authors: Ziming Liu, Yifan Yang, Chengruidong Zhang, Yiqi Zhang, Lili Qiu, Yang You,
  Yuqing Yang
conference: No Venue
year: 2025
bibkey: liu2025region
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.10389'}]
tags: ["Applications", "Training Techniques"]
short_authors: Liu et al.
---
Diffusion models (DMs) have become the leading choice for generative tasks across diverse domains. However, their reliance on multiple sequential forward passes significantly limits real-time performance. Previous acceleration methods have primarily focused on reducing the number of sampling steps or reusing intermediate results, failing to leverage variations across spatial regions within the image due to the constraints of convolutional U-Net structures. By harnessing the flexibility of Diffusion Transformers (DiTs) in handling variable number of tokens, we introduce RAS, a novel, training-free sampling strategy that dynamically assigns different sampling ratios to regions within an image based on the focus of the DiT model. Our key observation is that during each sampling step, the model concentrates on semantically meaningful regions, and these areas of focus exhibit strong continuity across consecutive steps. Leveraging this insight, RAS updates only the regions currently in focus, while other regions are updated using cached noise from the previous step. The model's focus is determined based on the output from the preceding step, capitalizing on the temporal consistency we observed. We evaluate RAS on Stable Diffusion 3 and Lumina-Next-T2I, achieving speedups up to 2.36x and 2.51x, respectively, with minimal degradation in generation quality. Additionally, a user study reveals that RAS delivers comparable qualities under human evaluation while achieving a 1.6x speedup. Our approach makes a significant step towards more efficient diffusion transformers, enhancing their potential for real-time applications.

https://huggingface.co/discussions/paper/67b2a8a4be31bfaa7cd2c1ad