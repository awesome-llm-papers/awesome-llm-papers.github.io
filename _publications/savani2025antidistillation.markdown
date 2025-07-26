---
layout: publication
title: Antidistillation Sampling
authors: Yash Savani, Asher Trockman, Zhili Feng, Avi Schwarzschild, Alexander Robey,
  Marc Finzi, J. Zico Kolter
conference: No Venue
year: 2025
bibkey: savani2025antidistillation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.13146'}]
tags: ["Efficiency", "Security"]
short_authors: Savani et al.
---
Frontier models that generate extended reasoning traces inadvertently produce rich token sequences that can facilitate model distillation. Recognizing this vulnerability, model owners may seek sampling strategies that limit the effectiveness of distillation without compromising model performance. Antidistillation sampling provides exactly this capability. By strategically modifying a model's next-token probability distribution, antidistillation sampling poisons reasoning traces, rendering them significantly less effective for distillation while preserving the model's practical utility. For further details, see https://antidistillation.com.

https://huggingface.co/discussions/paper/6801b77ecb758561ae269a19