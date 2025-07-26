---
layout: publication
title: 'Magictailor: Component-controllable Personalization In Text-to-image Diffusion
  Models'
authors: Donghao Zhou, Jiancheng Huang, Jinbin Bai, Jiaze Wang, Hao Chen, Guangyong
  Chen, Xiaowei Hu, Pheng-ann Heng
conference: No Venue
year: 2024
bibkey: zhou2024magictailor
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.13370'}]
tags: ["Applications", "Tools"]
short_authors: Zhou et al.
---
Recent advancements in text-to-image (T2I) diffusion models have enabled the creation of high-quality images from text prompts, but they still struggle to generate images with precise control over specific visual concepts. Existing approaches can replicate a given concept by learning from reference images, yet they lack the flexibility for fine-grained customization of the individual component within the concept. In this paper, we introduce component-controllable personalization, a novel task that pushes the boundaries of T2I models by allowing users to reconfigure specific components when personalizing visual concepts. This task is particularly challenging due to two primary obstacles: semantic pollution, where unwanted visual elements corrupt the personalized concept, and semantic imbalance, which causes disproportionate learning of the concept and component. To overcome these challenges, we design MagicTailor, an innovative framework that leverages Dynamic Masked Degradation (DM-Deg) to dynamically perturb undesired visual semantics and Dual-Stream Balancing (DS-Bal) to establish a balanced learning paradigm for desired visual semantics. Extensive comparisons, ablations, and analyses demonstrate that MagicTailor not only excels in this challenging task but also holds significant promise for practical applications, paving the way for more nuanced and creative image generation.

https://huggingface.co/discussions/paper/671361879186942050bfef20