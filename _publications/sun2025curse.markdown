---
layout: publication
title: The Curse Of Depth In Large Language Models
authors: Wenfang Sun, Xinyuan Song, Pengxiang Li, Lu Yin, Yefeng Zheng, Shiwei Liu
conference: No Venue
year: 2025
bibkey: sun2025curse
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.05795'}]
tags: ["Model Architecture"]
short_authors: Sun et al.
---
In this paper, we introduce the Curse of Depth, a concept that highlights, explains, and addresses the recent observation in modern Large Language Models(LLMs) where nearly half of the layers are less effective than expected. We first confirm the wide existence of this phenomenon across the most popular families of LLMs such as Llama, Mistral, DeepSeek, and Qwen. Our analysis, theoretically and empirically, identifies that the underlying reason for the ineffectiveness of deep layers in LLMs is the widespread usage of Pre-Layer Normalization (Pre-LN). While Pre-LN stabilizes the training of Transformer LLMs, its output variance exponentially grows with the model depth, which undesirably causes the derivative of the deep Transformer blocks to be an identity matrix, and therefore barely contributes to the training. To resolve this training pitfall, we propose LayerNorm Scaling, which scales the variance of output of the layer normalization inversely by the square root of its depth. This simple modification mitigates the output variance explosion of deeper Transformer layers, improving their contribution. Our experimental results, spanning model sizes from 130M to 1B, demonstrate that LayerNorm Scaling significantly enhances LLM pre-training performance compared to Pre-LN. Moreover, this improvement seamlessly carries over to supervised fine-tuning. All these gains can be attributed to the fact that LayerNorm Scaling enables deeper layers to contribute more effectively during training.

https://huggingface.co/discussions/paper/67ab189b8087b66340398b3b