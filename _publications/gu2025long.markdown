---
layout: publication
title: Long-context Autoregressive Video Modeling With Next-frame Prediction
authors: Yuchao Gu, Weijia Mao, Mike Zheng Shou
conference: No Venue
year: 2025
bibkey: gu2025long
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67e35f72c9d8214b5e1c659b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.19325'}]
tags: ["Memory & Context", "Training Techniques"]
short_authors: Yuchao Gu, Weijia Mao, Mike Zheng Shou
---
Long-context autoregressive modeling has significantly advanced language generation, but video generation still struggles to fully utilize extended temporal contexts. To investigate long-context video modeling, we introduce Frame AutoRegressive (FAR), a strong baseline for video autoregressive modeling. Just as language models learn causal dependencies between tokens (i.e., Token AR), FAR models temporal causal dependencies between continuous frames, achieving better convergence than Token AR and video diffusion transformers. Building on FAR, we observe that long-context vision modeling faces challenges due to visual redundancy. Existing RoPE lacks effective temporal decay for remote context and fails to extrapolate well to long video sequences. Additionally, training on long videos is computationally expensive, as vision tokens grow much faster than language tokens. To tackle these issues, we propose balancing locality and long-range dependency. We introduce FlexRoPE, an test-time technique that adds flexible temporal decay to RoPE, enabling extrapolation to 16x longer vision contexts. Furthermore, we propose long short-term context modeling, where a high-resolution short-term context window ensures fine-grained temporal consistency, while an unlimited long-term context window encodes long-range information using fewer tokens. With this approach, we can train on long video sequences with a manageable token context length. We demonstrate that FAR achieves state-of-the-art performance in both short- and long-video generation, providing a simple yet effective baseline for video autoregressive modeling.

https://huggingface.co/discussions/paper/67e35f72c9d8214b5e1c659b