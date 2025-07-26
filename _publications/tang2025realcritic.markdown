---
layout: publication
title: 'Realcritic: Towards Effectiveness-driven Evaluation Of Language Model Critiques'
authors: Zhengyang Tang, Ziniu Li, Zhenyang Xiao, Tian Ding, Ruoyu Sun, Benyou Wang,
  Dayiheng Liu, Fei Huang, Tianyu Liu, Bowen Yu, Junyang Lin
conference: No Venue
year: 2025
bibkey: tang2025realcritic
additional_links: [{name: Code, url: 'https://github.com/tangzhy/RealCritic'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6796fdb8582fda525a7f6496'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.14492'}]
tags: ["Evaluation", "Has Code"]
short_authors: Tang et al.
---
Critiques are important for enhancing the performance of Large Language Models (LLMs), enabling both self-improvement and constructive feedback for others by identifying flaws and suggesting improvements. However, evaluating the critique capabilities of LLMs presents a significant challenge due to the open-ended nature of the task. In this work, we introduce a new benchmark designed to assess the critique capabilities of LLMs. Unlike existing benchmarks, which typically function in an open-loop fashion, our approach employs a closed-loop methodology that evaluates the quality of corrections generated from critiques. Moreover, the benchmark incorporates features such as self-critique, cross-critique, and iterative critique, which are crucial for distinguishing the abilities of advanced reasoning models from more classical ones. We implement this benchmark using eight challenging reasoning tasks. We have several interesting findings. First, despite demonstrating comparable performance in direct chain-of-thought generation, classical LLMs significantly lag behind the advanced reasoning-based model o1-mini across all critique scenarios. Second, in self-critique and iterative critique settings, classical LLMs may even underperform relative to their baseline capabilities. We hope that this benchmark will serve as a valuable resource to guide future advancements. The code and data are available at https://github.com/tangzhy/RealCritic.

https://huggingface.co/discussions/paper/6796fdb8582fda525a7f6496