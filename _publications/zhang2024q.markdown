---
layout: publication
title: 'Q-galore: Quantized Galore With INT4 Projection And Layer-adaptive Low-rank
  Gradients'
authors: Zhenyu Zhang, Ajay Jaiswal, Lu Yin, Shiwei Liu, Jiawei Zhao, Yuandong Tian,
  Zhangyang Wang
conference: No Venue
year: 2024
bibkey: zhang2024q
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.08296'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Zhang et al.
---
Training Large Language Models (LLMs) is memory-intensive due to the large number of parameters and associated optimization states. GaLore, a recent method, reduces memory usage by projecting weight gradients into a low-rank subspace without compromising performance. However, GaLore relies on time-consuming Singular Value Decomposition (SVD) operations to identify the subspace, and the frequent subspace updates lead to significant training time overhead. Moreover, GaLore offers minimal improvements in accuracy and efficiency compared to LoRA in more accessible fine-tuning scenarios. To address these limitations, we introduce Q-Galore, a novel approach that substantially reduces memory usage by combining quantization and low-rank projection, surpassing the benefits of GaLore. Our method is based on two key observations: (i) the gradient subspace exhibits diverse properties, with some layers converging early in training while others are subject to frequent changes; (ii) the projection matrices are highly resilient to low-bit quantization. Leveraging these insights, Q-GaLore adaptively updates the gradient subspace based on its convergence statistics, achieving comparable performance while significantly reducing the number of SVD operations. We maintain the projection matrices in INT4 format and weights in INT8 format, incorporating stochastic rounding to capture accumulated gradient information. This approach enables a high-precision training trajectory using only low-precision weights. We demonstrate that Q-GaLore achieves highly competitive performance with exceptional memory efficiency. At pre-training, Q-GaLore facilitates training a LLaMA-7B model from scratch on a single NVIDIA RTX 4060 Ti with only 16 GB memory. At fine-tuning, it reduces memory consumption by up to 50% compared to LoRA and GaLore, while consistently outperforming QLoRA at the same memory cost.

https://huggingface.co/discussions/paper/6690b32e21b555734230474e