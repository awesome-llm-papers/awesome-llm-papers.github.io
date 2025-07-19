---
layout: publication
title: 'Eaquant: Enhancing Post-training Quantization For Moe Models Via Expert-aware
  Optimization'
authors: Fu et al.
conference: Machine Learning
year: 2025
bibkey: fu2025eaquant
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.13329'}]
tags: [RAG, Training Techniques, Tools, Model Architecture, ICML, Efficiency And Optimization,
  Reinforcement Learning, Quantization]
---
Mixture-of-Experts (MoE) models have emerged as a cornerstone of large-scale deep learning by efficiently distributing computation and enhancing performance. However, their unique architecture-characterized by sparse expert activation and dynamic routing mechanisms-introduces inherent complexities that challenge conventional quantization techniques. Existing post-training quantization (PTQ) methods struggle to address activation outliers, router consistency and sparse expert calibration, leading to significant performance degradation. To bridge this gap, we propose EAQuant, a novel PTQ framework tailored for MoE architectures. Our method systematically tackles these challenges through three key innovations: (1) expert-aware smoothing aggregation to suppress activation outliers and stabilize quantization, (2) router logits distribution alignment to preserve expert selection consistency post-quantization, and (3) expert-level calibration data balance to optimize sparsely activated experts. Extensive experiments across W4A4 and extreme W3A4 quantization configurations demonstrate that EAQuant significantly outperforms existing methods, achieving average score improvements of 1.15 - 2.28% across three diverse MoE architectures, with particularly pronounced gains in reasoning tasks and robust performance retention under aggressive quantization. By integrating these innovations, EAQuant establishes a new state-of-the-art for high-precision, efficient MoE model compression. Our code is available at https://github.com/darren-fzq1/EAQuant.