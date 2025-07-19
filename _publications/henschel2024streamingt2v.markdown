---
layout: publication
title: 'Streamingt2v: Consistent, Dynamic, And Extendable Long Video Generation From
  Text'
authors: Henschel et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: henschel2024streamingt2v
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.14773'}]
tags: [Attention Mechanism, GPT, Model Architecture, AAAI, Merging]
---
Text-to-video diffusion models enable the generation of high-quality videos
that follow text instructions, making it easy to create diverse and individual
content. However, existing approaches mostly focus on high-quality short video
generation (typically 16 or 24 frames), ending up with hard-cuts when naively
extended to the case of long video synthesis. To overcome these limitations, we
introduce StreamingT2V, an autoregressive approach for long video generation of
80, 240, 600, 1200 or more frames with smooth transitions. The key components
are:(i) a short-term memory block called conditional attention module (CAM),
which conditions the current generation on the features extracted from the
previous chunk via an attentional mechanism, leading to consistent chunk
transitions, (ii) a long-term memory block called appearance preservation
module, which extracts high-level scene and object features from the first
video chunk to prevent the model from forgetting the initial scene, and (iii) a
randomized blending approach that enables to apply a video enhancer
autoregressively for infinitely long videos without inconsistencies between
chunks. Experiments show that StreamingT2V generates high motion amount. In
contrast, all competing image-to-video methods are prone to video stagnation
when applied naively in an autoregressive manner. Thus, we propose with
StreamingT2V a high-quality seamless text-to-long video generator that
outperforms competitors with consistency and motion. Our code will be available
at: https://github.com/Picsart-AI-Research/StreamingT2V