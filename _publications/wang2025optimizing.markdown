---
layout: publication
title: Optimizing Large Language Model Training Using FP4 Quantization
authors: Ruizhe Wang, Yeyun Gong, Xiao Liu, Guoshuai Zhao, Ziyue Yang, Baining Guo,
  Zhengjun Zha, Peng Cheng
conference: No Venue
year: 2025
bibkey: wang2025optimizing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.17116'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Wang et al.
---
The growing computational demands of training large language models (LLMs) necessitate more efficient methods. Quantized training presents a promising solution by enabling low-bit arithmetic operations to reduce these costs. While FP8 precision has demonstrated feasibility, leveraging FP4 remains a challenge due to significant quantization errors and limited representational capacity. This work introduces the first FP4 training framework for LLMs, addressing these challenges with two key innovations: a differentiable quantization estimator for precise weight updates and an outlier clamping and compensation strategy to prevent activation collapse. To ensure stability, the framework integrates a mixed-precision training scheme and vector-wise quantization. Experimental results demonstrate that our FP4 framework achieves accuracy comparable to BF16 and FP8, with minimal degradation, scaling effectively to 13B-parameter LLMs trained on up to 100B tokens. With the emergence of next-generation hardware supporting FP4, our framework sets a foundation for efficient ultra-low precision training.

https://huggingface.co/discussions/paper/6799b368d30dc065a2d515bf