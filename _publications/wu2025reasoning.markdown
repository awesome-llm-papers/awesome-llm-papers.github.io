---
layout: publication
title: Reasoning Or Memorization? Unreliable Results Of Reinforcement Learning Due
  To Data Contamination
authors: Mingqi Wu, Zhihao Zhang, Qiaole Dong, Zhiheng Xi, Jun Zhao, Senjie Jin, Xiaoran
  Fan, Yuhao Zhou, Yanwei Fu, Qin Liu, Songyang Zhang, Qi Zhang
conference: No Venue
year: 2025
bibkey: wu2025reasoning
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6875f107257d4f043537061f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.10532'}]
tags: ["Reinforcement Learning"]
short_authors: Wu et al.
---
The reasoning capabilities of large language models (LLMs) have been a longstanding focus of research. Recent works have further enhanced these capabilities using reinforcement learning (RL), with many new methods claiming significant improvements with minimal or no external supervision. Surprisingly, some studies even suggest that random or incorrect reward signals can enhance reasoning performance. However, these breakthroughs are mostly reported on the Qwen2.5 model family and evaluated on well-known benchmarks such as MATH-500, AMC, and AIME, while failing to achieve similar gains on other models like Llama, which warrants further investigation. Our analysis shows that although Qwen2.5 achieves strong mathematical reasoning performance, its pretraining on large-scale web corpora makes it vulnerable to data contamination in popular benchmarks. As a result, results derived from these benchmarks may be unreliable. To address this, we introduce a generator that produces fully synthetic arithmetic problems of arbitrary length and difficulty, yielding a clean dataset we call RandomCalculation. Using these leakage-free datasets, we show that only accurate reward signals consistently improve performance, while noisy or incorrect signals do not. We advocate for evaluating RL methods on uncontaminated benchmarks and across diverse model families to ensure trustworthy conclusions.

https://huggingface.co/discussions/paper/6875f107257d4f043537061f