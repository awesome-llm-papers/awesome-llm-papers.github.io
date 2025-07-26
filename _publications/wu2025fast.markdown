---
layout: publication
title: 'Fast-dllm: Training-free Acceleration Of Diffusion LLM By Enabling KV Cache
  And Parallel Decoding'
authors: Chengyue Wu, Hao Zhang, Shuchen Xue, Zhijian Liu, Shizhe Diao, Ligeng Zhu,
  Ping Luo, Song Han, Enze Xie
conference: No Venue
year: 2025
bibkey: wu2025fast
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/683931e2b6280677f75edf32'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.22618'}]
tags: ["Memory & Context", "Training Techniques"]
short_authors: Wu et al.
---
Diffusion-based large language models (Diffusion LLMs) have shown promise for non-autoregressive text generation with parallel decoding capabilities. However, the practical inference speed of open-sourced Diffusion LLMs often lags behind autoregressive models due to the lack of Key-Value (KV) Cache and quality degradation when decoding multiple tokens simultaneously. To bridge this gap, we introduce a novel block-wise approximate KV Cache mechanism tailored for bidirectional diffusion models, enabling cache reuse with negligible performance drop. Additionally, we identify the root cause of generation quality degradation in parallel decoding as the disruption of token dependencies under the conditional independence assumption. To address this, we propose a confidence-aware parallel decoding strategy that selectively decodes tokens exceeding a confidence threshold, mitigating dependency violations and maintaining generation quality. Experimental results on LLaDA and Dream models across multiple LLM benchmarks demonstrate up to 27.6times throughput improvement with minimal accuracy loss, closing the performance gap with autoregressive models and paving the way for practical deployment of Diffusion LLMs.

https://huggingface.co/discussions/paper/683931e2b6280677f75edf32