---
layout: publication
title: 'Reinforcement Learning For Reasoning In Small Llms: What Works And What Doesn''t'
authors: Quy-anh Dang, Chris Ngo
conference: No Venue
year: 2025
bibkey: dang2025reinforcement
additional_links: [{name: Code, url: 'https://github.com/knoveleng/open-rs'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67dd1a9dfa598c90d14e9ba4'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.16219'}]
tags: ["Reinforcement Learning"]
short_authors: Quy-anh Dang, Chris Ngo
---
Enhancing the reasoning capabilities of large language models (LLMs) typically relies on massive computational resources and extensive datasets, limiting accessibility for resource-constrained settings. Our study investigates the potential of reinforcement learning (RL) to improve reasoning in small LLMs, focusing on a 1.5-billion-parameter model, DeepSeek-R1-Distill-Qwen-1.5B, under strict constraints: training on 4 NVIDIA A40 GPUs (48 GB VRAM each) within 24 hours. Adapting the Group Relative Policy Optimization (GRPO) algorithm and curating a compact, high-quality mathematical reasoning dataset, we conducted three experiments to explore model behavior and performance. Our results demonstrate rapid reasoning gains - e.g., AMC23 accuracy rising from 63% to 80% and AIME24 reaching 46.7%, surpassing o1-preview - using only 7,000 samples and a $42 training cost, compared to thousands of dollars for baseline models. However, challenges such as optimization instability and length constraints emerged with prolonged training. These findings highlight the efficacy of RL-based fine-tuning for small LLMs, offering a cost-effective alternative to large-scale approaches. We release our code and datasets as open-source resources, providing insights into trade-offs and laying a foundation for scalable, reasoning-capable LLMs in resource-limited environments. All are available at https://github.com/knoveleng/open-rs.

https://huggingface.co/discussions/paper/67dd1a9dfa598c90d14e9ba4