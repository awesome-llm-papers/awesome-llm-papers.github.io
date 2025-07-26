---
layout: publication
title: Quantization Hurts Reasoning? An Empirical Study On Quantized Reasoning Models
authors: Ruikang Liu, Yuxuan Sun, Manyi Zhang, Haoli Bai, Xianzhi Yu, Tiezheng Yu,
  Chun Yuan, Lu Hou
conference: No Venue
year: 2025
bibkey: liu2025quantization
additional_links: [{name: Code, url: 'https://github.com/ruikangliu/Quantized-Reasoning-Models'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67f4a8efd83d88e30c45043c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.04823'}]
tags: ["Evaluation"]
short_authors: Liu et al.
---
Recent advancements in reasoning language models have demonstrated remarkable performance in complex tasks, but their extended chain-of-thought reasoning process increases inference overhead. While quantization has been widely adopted to reduce the inference cost of large language models, its impact on reasoning models remains understudied. In this study, we conduct the first systematic study on quantized reasoning models, evaluating the open-sourced DeepSeek-R1-Distilled Qwen and LLaMA families ranging from 1.5B to 70B parameters, and QwQ-32B. Our investigation covers weight, KV cache, and activation quantization using state-of-the-art algorithms at varying bit-widths, with extensive evaluation across mathematical (AIME, MATH-500), scientific (GPQA), and programming (LiveCodeBench) reasoning benchmarks. Our findings reveal that while lossless quantization can be achieved with W8A8 or W4A16 quantization, lower bit-widths introduce significant accuracy risks. We further identify model size, model origin, and task difficulty as critical determinants of performance. Contrary to expectations, quantized models do not exhibit increased output lengths. In addition, strategically scaling the model sizes or reasoning steps can effectively enhance the performance. All quantized models and codes will be open-sourced in https://github.com/ruikangliu/Quantized-Reasoning-Models.

https://huggingface.co/discussions/paper/67f4a8efd83d88e30c45043c