---
layout: publication
title: 'Skyreels-a2: Compose Anything In Video Diffusion Transformers'
authors: Zhengcong Fei, Debang Li, di Qiu, Jiahua Wang, Yikun Dou, Rui Wang, Jingtao
  Xu, Mingyuan Fan, Guibin Chen, Yang Li, Yahui Zhou
conference: No Venue
year: 2025
bibkey: fei2025skyreels
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.02436'}]
tags: ["Applications", "Tools"]
short_authors: Fei et al.
---
This paper presents SkyReels-A2, a controllable video generation framework capable of assembling arbitrary visual elements (e.g., characters, objects, backgrounds) into synthesized videos based on textual prompts while maintaining strict consistency with reference images for each element. We term this task elements-to-video (E2V), whose primary challenges lie in preserving the fidelity of each reference element, ensuring coherent composition of the scene, and achieving natural outputs. To address these, we first design a comprehensive data pipeline to construct prompt-reference-video triplets for model training. Next, we propose a novel image-text joint embedding model to inject multi-element representations into the generative process, balancing element-specific consistency with global coherence and text alignment. We also optimize the inference pipeline for both speed and output stability. Moreover, we introduce a carefully curated benchmark for systematic evaluation, i.e, A2 Bench. Experiments demonstrate that our framework can generate diverse, high-quality videos with precise element control. SkyReels-A2 is the first open-source commercial grade model for the generation of E2V, performing favorably against advanced closed-source commercial models. We anticipate SkyReels-A2 will advance creative applications such as drama and virtual e-commerce, pushing the boundaries of controllable video generation.

https://huggingface.co/discussions/paper/67ef3dfee8b932ae7a832a97