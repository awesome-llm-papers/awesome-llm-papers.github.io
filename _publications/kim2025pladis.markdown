---
layout: publication
title: 'PLADIS: Pushing The Limits Of Attention In Diffusion Models At Inference Time
  By Leveraging Sparsity'
authors: Kwanyoung Kim, Byeongsu Sim
conference: No Venue
year: 2025
bibkey: kim2025pladis
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.07677'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Kwanyoung Kim, Byeongsu Sim
---
Diffusion models have shown impressive results in generating high-quality conditional samples using guidance techniques such as Classifier-Free Guidance (CFG). However, existing methods often require additional training or neural function evaluations (NFEs), making them incompatible with guidance-distilled models. Also, they rely on heuristic approaches that need identifying target layers. In this work, we propose a novel and efficient method, termed PLADIS, which boosts pre-trained models (U-Net/Transformer) by leveraging sparse attention. Specifically, we extrapolate query-key correlations using softmax and its sparse counterpart in the cross-attention layer during inference, without requiring extra training or NFEs. By leveraging the noise robustness of sparse attention, our PLADIS unleashes the latent potential of text-to-image diffusion models, enabling them to excel in areas where they once struggled with newfound effectiveness. It integrates seamlessly with guidance techniques, including guidance-distilled models. Extensive experiments show notable improvements in text alignment and human preference, offering a highly efficient and universally applicable solution.

https://huggingface.co/discussions/paper/67d2ca0b67366130cccada34