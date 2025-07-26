---
layout: publication
title: 'Prefixquant: Static Quantization Beats Dynamic Through Prefixed Outliers In
  Llms'
authors: Mengzhao Chen, Yi Liu, Jiahao Wang, Yi Bin, Wenqi Shao, Ping Luo
conference: No Venue
year: 2024
bibkey: chen2024prefixquant
additional_links: [{name: Code, url: 'https://github.com/ChenMnZ/PrefixQuant'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/67089019f5c3ffa260bc5967'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.05265'}]
tags: ["Training Techniques"]
short_authors: Chen et al.
---
Quantization is essential for deploying Large Language Models (LLMs) by enhancing memory efficiency and inference speed. Existing methods for activation quantization mainly address channel-wise outliers, often neglecting token-wise outliers, leading to reliance on costly per-token dynamic quantization. To address this, we introduce PrefixQuant, a novel technique that isolates outlier tokens offline without re-training. Specifically, PrefixQuant identifies high-frequency outlier tokens and prefixes them in the KV cache, preventing the generation of outlier tokens during inference and simplifying quantization. To our knowledge, PrefixQuant is the first to enable efficient per-tensor static quantization to outperform expensive per-token dynamic quantization. For instance, in W4A4KV4 (4- bit weight, 4-bit activation, and 4-bit KV cache) Llama-3-8B, PrefixQuant with per-tensor static quantization achieves a 7.43 WikiText2 perplexity and 71.08% average accuracy on 5 common-sense reasoning tasks, outperforming previous per-token dynamic quantization methods like QuaRot with 0.98 perplexity improvement and +5.98 points accuracy. Additionally, the inference speed of W4A4 quantized models using PrefixQuant is 1.60x to 2.81x faster than FP16 models and exceeds QuaRot models by 1.2x to 1.3x. Our code is available at https://github.com/ChenMnZ/PrefixQuant.

https://huggingface.co/discussions/paper/67089019f5c3ffa260bc5967