---
layout: publication
title: 'Itercomp: Iterative Composition-aware Feedback Learning From Model Gallery
  For Text-to-image Generation'
authors: Xinchen Zhang, Ling Yang, Guohao Li, Yaqi Cai, Jiake Xie, Yong Tang, Yujiu
  Yang, Mengdi Wang, Bin Cui
conference: No Venue
year: 2024
bibkey: zhang2024itercomp
additional_links: [{name: Code, url: 'https://github.com/YangLing0818/IterComp'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67073ff1327cec6882ea2d3b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.07171'}]
tags: ["Tools"]
short_authors: Zhang et al.
---
Advanced diffusion models like RPG, Stable Diffusion 3 and FLUX have made notable strides in compositional text-to-image generation. However, these methods typically exhibit distinct strengths for compositional generation, with some excelling in handling attribute binding and others in spatial relationships. This disparity highlights the need for an approach that can leverage the complementary strengths of various models to comprehensively improve the composition capability. To this end, we introduce IterComp, a novel framework that aggregates composition-aware model preferences from multiple models and employs an iterative feedback learning approach to enhance compositional generation. Specifically, we curate a gallery of six powerful open-source diffusion models and evaluate their three key compositional metrics: attribute binding, spatial relationships, and non-spatial relationships. Based on these metrics, we develop a composition-aware model preference dataset comprising numerous image-rank pairs to train composition-aware reward models. Then, we propose an iterative feedback learning method to enhance compositionality in a closed-loop manner, enabling the progressive self-refinement of both the base diffusion model and reward models over multiple iterations. Theoretical proof demonstrates the effectiveness and extensive experiments show our significant superiority over previous SOTA methods (e.g., Omost and FLUX), particularly in multi-category object composition and complex semantic alignment. IterComp opens new research avenues in reward feedback learning for diffusion models and compositional generation. Code: https://github.com/YangLing0818/IterComp

https://huggingface.co/discussions/paper/67073ff1327cec6882ea2d3b