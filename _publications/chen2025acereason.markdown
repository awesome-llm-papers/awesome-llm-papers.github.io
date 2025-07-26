---
layout: publication
title: 'Acereason-nemotron: Advancing Math And Code Reasoning Through Reinforcement
  Learning'
authors: Yang Chen, Zhuolin Yang, Zihan Liu, Chankyu Lee, Peng Xu, Mohammad Shoeybi,
  Bryan Catanzaro, Wei Ping
conference: No Venue
year: 2025
bibkey: chen2025acereason
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/682fe6654640a9db4d1f3229'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.16400'}]
tags: ["Efficiency", "Reinforcement Learning", "Training Techniques"]
short_authors: Chen et al.
---
Despite recent progress in large-scale reinforcement learning (RL) for reasoning, the training recipe for building high-performing reasoning models remains elusive. Key implementation details of frontier models, such as DeepSeek-R1, including data curation strategies and RL training recipe, are often omitted. Moreover, recent research indicates distillation remains more effective than RL for smaller models. In this work, we demonstrate that large-scale RL can significantly enhance the reasoning capabilities of strong, small- and mid-sized models, achieving results that surpass those of state-of-the-art distillation-based models. We systematically study the RL training process through extensive ablations and propose a simple yet effective approach: first training on math-only prompts, then on code-only prompts. Notably, we find that math-only RL not only significantly enhances the performance of strong distilled models on math benchmarks (e.g., +14.6% / +17.2% on AIME 2025 for the 7B / 14B models), but also code reasoning tasks (e.g., +6.8% / +5.8% on LiveCodeBench for the 7B / 14B models). In addition, extended code-only RL iterations further improve performance on code benchmarks with minimal or no degradation in math results. We develop a robust data curation pipeline to collect challenging prompts with high-quality, verifiable answers and test cases to enable verification-based RL across both domains. Finally, we identify key experimental insights, including curriculum learning with progressively increasing response lengths and the stabilizing effect of on-policy parameter updates. We find that RL not only elicits the foundational reasoning capabilities acquired during pretraining and supervised fine-tuning (e.g., distillation), but also pushes the limits of the model's reasoning ability, enabling it to solve problems that were previously unsolvable.

https://huggingface.co/discussions/paper/682fe6654640a9db4d1f3229