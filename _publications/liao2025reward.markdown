---
layout: publication
title: Reward-guided Speculative Decoding For Efficient LLM Reasoning
authors: Baohao Liao, Yuhui Xu, Hanze Dong, Junnan Li, Christof Monz, Silvio Savarese,
  Doyen Sahoo, Caiming Xiong
conference: No Venue
year: 2025
bibkey: liao2025reward
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.19324'}]
tags: ["Efficiency", "Reinforcement Learning"]
short_authors: Liao et al.
---
We introduce Reward-Guided Speculative Decoding (RSD), a novel framework aimed at improving the efficiency of inference in large language models (LLMs). RSD synergistically combines a lightweight draft model with a more powerful target model, incorporating a controlled bias to prioritize high-reward outputs, in contrast to existing speculative decoding methods that enforce strict unbiasedness. RSD employs a process reward model to evaluate intermediate decoding steps and dynamically decide whether to invoke the target model, optimizing the trade-off between computational cost and output quality. We theoretically demonstrate that a threshold-based mixture strategy achieves an optimal balance between resource utilization and performance. Extensive evaluations on challenging reasoning benchmarks, including Olympiad-level tasks, show that RSD delivers significant efficiency gains against decoding with the target model only (up to 4.4x fewer FLOPs), while achieving significant better accuracy than parallel decoding method on average (up to +3.5). These results highlight RSD as a robust and cost-effective approach for deploying LLMs in resource-intensive scenarios.

https://huggingface.co/discussions/paper/67a04152dd7b3a4aba8805c0