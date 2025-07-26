---
layout: publication
title: 'Beyond ''aha!'': Toward Systematic Meta-abilities Alignment In Large Reasoning
  Models'
authors: Zhiyuan Hu, Yibo Wang, Hanze Dong, Yuhui Xu, Amrita Saha, Caiming Xiong,
  Bryan Hooi, Junnan Li
conference: No Venue
year: 2025
bibkey: hu2025beyond
additional_links: [{name: Code, url: 'https://github.com/zhiyuanhubj/Meta-Ability-Alignment'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6826a56aea77771e3880f7c8'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.10554'}]
tags: ["Emergent Abilities"]
short_authors: Hu et al.
---
Large reasoning models (LRMs) already possess a latent capacity for long chain-of-thought reasoning. Prior work has shown that outcome-based reinforcement learning (RL) can incidentally elicit advanced reasoning behaviors such as self-correction, backtracking, and verification phenomena often referred to as the model's "aha moment". However, the timing and consistency of these emergent behaviors remain unpredictable and uncontrollable, limiting the scalability and reliability of LRMs' reasoning capabilities. To address these limitations, we move beyond reliance on prompts and coincidental "aha moments". Instead, we explicitly align models with three meta-abilities: deduction, induction, and abduction, using automatically generated, self-verifiable tasks. Our three stage-pipeline individual alignment, parameter-space merging, and domain-specific reinforcement learning, boosting performance by over 10% relative to instruction-tuned baselines. Furthermore, domain-specific RL from the aligned checkpoint yields an additional 2% average gain in the performance ceiling across math, coding, and science benchmarks, demonstrating that explicit meta-ability alignment offers a scalable and dependable foundation for reasoning. Code is available at: https://github.com/zhiyuanhubj/Meta-Ability-Alignment

https://huggingface.co/discussions/paper/6826a56aea77771e3880f7c8