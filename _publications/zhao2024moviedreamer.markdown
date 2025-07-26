---
layout: publication
title: 'Moviedreamer: Hierarchical Generation For Coherent Long Visual Sequence'
authors: Canyu Zhao, Mingyu Liu, Wen Wang, Jianlong Yuan, Hao Chen, Bo Zhang, Chunhua
  Shen
conference: No Venue
year: 2024
bibkey: zhao2024moviedreamer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.16655'}]
tags: ["Has Code", "Tools"]
short_authors: Zhao et al.
---
Recent advancements in video generation have primarily leveraged diffusion models for short-duration content. However, these approaches often fall short in modeling complex narratives and maintaining character consistency over extended periods, which is essential for long-form video production like movies. We propose MovieDreamer, a novel hierarchical framework that integrates the strengths of autoregressive models with diffusion-based rendering to pioneer long-duration video generation with intricate plot progressions and high visual fidelity. Our approach utilizes autoregressive models for global narrative coherence, predicting sequences of visual tokens that are subsequently transformed into high-quality video frames through diffusion rendering. This method is akin to traditional movie production processes, where complex stories are factorized down into manageable scene capturing. Further, we employ a multimodal script that enriches scene descriptions with detailed character information and visual style, enhancing continuity and character identity across scenes. We present extensive experiments across various movie genres, demonstrating that our approach not only achieves superior visual and narrative quality but also effectively extends the duration of generated content significantly beyond current capabilities. Homepage: https://aim-uofa.github.io/MovieDreamer/.

https://huggingface.co/discussions/paper/66a05db4cf52b98e1d2875ab