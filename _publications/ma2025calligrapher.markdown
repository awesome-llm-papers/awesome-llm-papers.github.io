---
layout: publication
title: 'Calligrapher: Freestyle Text Image Customization'
authors: Yue Ma, Qingyan Bai, Hao Ouyang, Ka Leong Cheng, Qiuyu Wang, Hongyu Liu,
  Zichen Liu, Haofan Wang, Jingye Chen, Yujun Shen, Qifeng Chen
conference: No Venue
year: 2025
bibkey: ma2025calligrapher
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68634673588cea0da970c86d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.24123'}]
tags: ["Applications", "Tools"]
short_authors: Ma et al.
---
We introduce Calligrapher, a novel diffusion-based framework that innovatively integrates advanced text customization with artistic typography for digital calligraphy and design applications. Addressing the challenges of precise style control and data dependency in typographic customization, our framework incorporates three key technical contributions. First, we develop a self-distillation mechanism that leverages the pre-trained text-to-image generative model itself alongside the large language model to automatically construct a style-centric typography benchmark. Second, we introduce a localized style injection framework via a trainable style encoder, which comprises both Qformer and linear layers, to extract robust style features from reference images. An in-context generation mechanism is also employed to directly embed reference images into the denoising process, further enhancing the refined alignment of target styles. Extensive quantitative and qualitative evaluations across diverse fonts and design contexts confirm Calligrapher's accurate reproduction of intricate stylistic details and precise glyph positioning. By automating high-quality, visually consistent typography, Calligrapher surpasses traditional models, empowering creative practitioners in digital art, branding, and contextual typographic design.

https://huggingface.co/discussions/paper/68634673588cea0da970c86d