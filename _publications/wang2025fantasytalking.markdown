---
layout: publication
title: 'Fantasytalking: Realistic Talking Portrait Generation Via Coherent Motion
  Synthesis'
authors: Mengchao Wang, Qiang Wang, Fan Jiang, Yaqi Fan, Yunpeng Zhang, Yonggang Qi,
  Kun Zhao, Mu Xu
conference: No Venue
year: 2025
bibkey: wang2025fantasytalking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.04842'}]
tags: ["Has Code", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Wang et al.
---
Creating a realistic animatable avatar from a single static portrait remains challenging. Existing approaches often struggle to capture subtle facial expressions, the associated global body movements, and the dynamic background. To address these limitations, we propose a novel framework that leverages a pretrained video diffusion transformer model to generate high-fidelity, coherent talking portraits with controllable motion dynamics. At the core of our work is a dual-stage audio-visual alignment strategy. In the first stage, we employ a clip-level training scheme to establish coherent global motion by aligning audio-driven dynamics across the entire scene, including the reference portrait, contextual objects, and background. In the second stage, we refine lip movements at the frame level using a lip-tracing mask, ensuring precise synchronization with audio signals. To preserve identity without compromising motion flexibility, we replace the commonly used reference network with a facial-focused cross-attention module that effectively maintains facial consistency throughout the video. Furthermore, we integrate a motion intensity modulation module that explicitly controls expression and body motion intensity, enabling controllable manipulation of portrait movements beyond mere lip motion. Extensive experimental results show that our proposed approach achieves higher quality with better realism, coherence, motion intensity, and identity preservation. Ours project page: https://fantasy-amap.github.io/fantasy-talking/.

https://huggingface.co/discussions/paper/67f72cac353d129fc7bdd60f