---
layout: publication
title: 'Style2code: A Style-controllable Code Generation Framework With Dual-modal
  Contrastive Representation Learning'
authors: Zhang Dutao, Kovalchuk Sergey, He Yulong
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: zhang2025style2code
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.19442'}]
tags: [Training Techniques, EMNLP, Tools, Reinforcement Learning, LLM For Code]
---
Controllable code generation, the ability to synthesize code that follows a specified style while maintaining functionality, remains a challenging task. We propose a two-stage training framework combining contrastive learning and conditional decoding to enable flexible style control. The first stage aligns code style representations with semantic and structural features. In the second stage, we fine-tune a language model (e.g., Flan-T5) conditioned on the learned style vector to guide generation. Our method supports style interpolation and user personalization via lightweight mixing. Compared to prior work, our unified framework offers improved stylistic control without sacrificing code correctness. This is among the first approaches to combine contrastive alignment with conditional decoding for style-guided code generation.