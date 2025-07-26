---
layout: publication
title: Does Math Reasoning Improve General LLM Capabilities? Understanding Transferability
  Of LLM Reasoning
authors: Maggie Huan, Yuetai Li, Tuney Zheng, Xiaoyu Xu, Seungone Kim, Minxin Du,
  Radha Poovendran, Graham Neubig, Xiang Yue
conference: No Venue
year: 2025
bibkey: huan2025does
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.00432'}]
tags: ["Agentic", "Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Huan et al.
---
Math reasoning has become the poster child of progress in large language models (LLMs), with new models rapidly surpassing human-level performance on benchmarks like MATH and AIME. But as math leaderboards improve week by week, it is worth asking: do these gains reflect broader problem-solving ability or just narrow overfitting? To answer this question, we evaluate over 20 open-weight reasoning-tuned models across a broad suite of tasks, including math, scientific QA, agent planning, coding, and standard instruction-following. We surprisingly find that most models that succeed in math fail to transfer their gains to other domains. To rigorously study this phenomenon, we conduct controlled experiments on Qwen3-14B models using math-only data but different tuning methods. We find that reinforcement learning (RL)-tuned models generalize well across domains, while supervised fine-tuning (SFT)-tuned models often forget general capabilities. Latent-space representation and token-space distribution shift analyses reveal that SFT induces substantial representation and output drift, while RL preserves general-domain structure. Our results suggest a need to rethink standard post-training recipes, particularly the reliance on SFT-distilled data for advancing reasoning models.

https://huggingface.co/discussions/paper/686490e9d59a9eda59024a6d