---
layout: publication
title: 'Reptext: Rendering Visual Text Via Replicating'
authors: Haofan Wang, Yujia Xu, Yimeng Li, Junchen Li, Chaowei Zhang, Jing Wang, Kejia
  Yang, Zhibo Chen
conference: No Venue
year: 2025
bibkey: wang2025reptext
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.19724'}]
tags: []
short_authors: Wang et al.
---
Although contemporary text-to-image generation models have achieved remarkable breakthroughs in producing visually appealing images, their capacity to generate precise and flexible typographic elements, especially non-Latin alphabets, remains constrained. To address these limitations, we start from an naive assumption that text understanding is only a sufficient condition for text rendering, but not a necessary condition. Based on this, we present RepText, which aims to empower pre-trained monolingual text-to-image generation models with the ability to accurately render, or more precisely, replicate, multilingual visual text in user-specified fonts, without the need to really understand them. Specifically, we adopt the setting from ControlNet and additionally integrate language agnostic glyph and position of rendered text to enable generating harmonized visual text, allowing users to customize text content, font and position on their needs. To improve accuracy, a text perceptual loss is employed along with the diffusion loss. Furthermore, to stabilize rendering process, at the inference phase, we directly initialize with noisy glyph latent instead of random initialization, and adopt region masks to restrict the feature injection to only the text region to avoid distortion of the background. We conducted extensive experiments to verify the effectiveness of our RepText relative to existing works, our approach outperforms existing open-source methods and achieves comparable results to native multi-language closed-source models. To be more fair, we also exhaustively discuss its limitations in the end.

https://huggingface.co/discussions/paper/68104ddfec94d9d54ebde3f3