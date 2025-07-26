---
layout: publication
title: 'Prorl: Prolonged Reinforcement Learning Expands Reasoning Boundaries In Large
  Language Models'
authors: Mingjie Liu, Shizhe Diao, Ximing Lu, Jian Hu, Xin Dong, Yejin Choi, Jan Kautz,
  Yi Dong
conference: No Venue
year: 2025
bibkey: liu2025prorl
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.24864'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Liu et al.
---
Recent advances in reasoning-centric language models have highlighted reinforcement learning (RL) as a promising method for aligning models with verifiable rewards. However, it remains contentious whether RL truly expands a model's reasoning capabilities or merely amplifies high-reward outputs already latent in the base model's distribution, and whether continually scaling up RL compute reliably leads to improved reasoning performance. In this work, we challenge prevailing assumptions by demonstrating that prolonged RL (ProRL) training can uncover novel reasoning strategies that are inaccessible to base models, even under extensive sampling. We introduce ProRL, a novel training methodology that incorporates KL divergence control, reference policy resetting, and a diverse suite of tasks. Our empirical analysis reveals that RL-trained models consistently outperform base models across a wide range of pass@k evaluations, including scenarios where base models fail entirely regardless of the number of attempts. We further show that reasoning boundary improvements correlates strongly with task competence of base model and training duration, suggesting that RL can explore and populate new regions of solution space over time. These findings offer new insights into the conditions under which RL meaningfully expands reasoning boundaries in language models and establish a foundation for future work on long-horizon RL for reasoning. We release model weights to support further research: https://huggingface.co/nvidia/Nemotron-Research-Reasoning-Qwen-1.5B

https://huggingface.co/discussions/paper/683d2d08ae87a04bca311bd4