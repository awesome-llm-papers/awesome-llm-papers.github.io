---
layout: publication
title: Fast Text-to-audio Generation With Adversarial Post-training
authors: Novack et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: novack2025fast
citations: 192
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.08175'}]
tags: [RAG, Training Techniques, Distillation, Prompting, Efficiency And Optimization,
  Applications, Security, AAAI, Merging]
---
Text-to-audio systems, while increasingly performant, are slow at inference time, thus making their latency unpractical for many creative applications. We present Adversarial Relativistic-Contrastive (ARC) post-training, the first adversarial acceleration algorithm for diffusion/flow models not based on distillation. While past adversarial post-training methods have struggled to compare against their expensive distillation counterparts, ARC post-training is a simple procedure that (1) extends a recent relativistic adversarial formulation to diffusion/flow post-training and (2) combines it with a novel contrastive discriminator objective to encourage better prompt adherence. We pair ARC post-training with a number optimizations to Stable Audio Open and build a model capable of generating \\(\approx\\)12s of 44.1kHz stereo audio in \\(\approx\\)75ms on an H100, and \\(\approx\\)7s on a mobile edge-device, the fastest text-to-audio model to our knowledge.