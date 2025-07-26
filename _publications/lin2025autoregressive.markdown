---
layout: publication
title: Autoregressive Adversarial Post-training For Real-time Interactive Video Generation
authors: Shanchuan Lin, Ceyuan Yang, Hao He, Jianwen Jiang, Yuxi Ren, Xin Xia, Yang
  Zhao, Xuefeng Xiao, Lu Jiang
conference: No Venue
year: 2025
bibkey: lin2025autoregressive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.09350'}]
tags: ["Applications", "Model Architecture", "Training Techniques"]
short_authors: Lin et al.
---
Existing large-scale video generation models are computationally intensive, preventing adoption in real-time and interactive applications. In this work, we propose autoregressive adversarial post-training (AAPT) to transform a pre-trained latent video diffusion model into a real-time, interactive video generator. Our model autoregressively generates a latent frame at a time using a single neural function evaluation (1NFE). The model can stream the result to the user in real time and receive interactive responses as controls to generate the next latent frame. Unlike existing approaches, our method explores adversarial training as an effective paradigm for autoregressive generation. This not only allows us to design an architecture that is more efficient for one-step generation while fully utilizing the KV cache, but also enables training the model in a student-forcing manner that proves to be effective in reducing error accumulation during long video generation. Our experiments demonstrate that our 8B model achieves real-time, 24fps, streaming video generation at 736x416 resolution on a single H100, or 1280x720 on 8xH100 up to a minute long (1440 frames). Visit our research website at https://seaweed-apt.com/2

https://huggingface.co/discussions/paper/684a79ca9b38e1e5a33a68c8