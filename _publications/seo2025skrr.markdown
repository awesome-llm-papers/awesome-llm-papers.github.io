---
layout: publication
title: 'Skrr: Skip And Re-use Text Encoder Layers For Memory Efficient Text-to-image
  Generation'
authors: Hoigi Seo, Wongi Jeong, Jae-sun Seo, Se Young Chun
conference: No Venue
year: 2025
bibkey: seo2025skrr
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67aec0a903bf3301ec29adf3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.08690'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Seo et al.
---
Large-scale text encoders in text-to-image (T2I) diffusion models have demonstrated exceptional performance in generating high-quality images from textual prompts. Unlike denoising modules that rely on multiple iterative steps, text encoders require only a single forward pass to produce text embeddings. However, despite their minimal contribution to total inference time and floating-point operations (FLOPs), text encoders demand significantly higher memory usage, up to eight times more than denoising modules. To address this inefficiency, we propose Skip and Re-use layers (Skrr), a simple yet effective pruning strategy specifically designed for text encoders in T2I diffusion models. Skrr exploits the inherent redundancy in transformer blocks by selectively skipping or reusing certain layers in a manner tailored for T2I tasks, thereby reducing memory consumption without compromising performance. Extensive experiments demonstrate that Skrr maintains image quality comparable to the original model even under high sparsity levels, outperforming existing blockwise pruning methods. Furthermore, Skrr achieves state-of-the-art memory efficiency while preserving performance across multiple evaluation metrics, including the FID, CLIP, DreamSim, and GenEval scores.

https://huggingface.co/discussions/paper/67aec0a903bf3301ec29adf3