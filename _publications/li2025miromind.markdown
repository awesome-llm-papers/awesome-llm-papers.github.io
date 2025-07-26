---
layout: publication
title: 'Miromind-m1: An Open-source Advancement In Mathematical Reasoning Via Context-aware
  Multi-stage Policy Optimization'
authors: Xingxuan Li, Yao Xiao, Dianwen Ng, Hai Ye, Yue Deng, Xiang Lin, Bin Wang,
  Zhanfeng Mo, Chong Zhang, Yueyi Zhang, Zonglin Yang, Ruilin Li, Lei Lei, Shihao
  Xu, Han Zhao, Weiling Chen, Feng Ji, Lidong Bing
conference: No Venue
year: 2025
bibkey: li2025miromind
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.14683'}]
tags: ["Datasets", "Efficiency", "Ethics & Fairness", "Evaluation", "Fine-Tuning", "Model Architecture", "Prompting", "Reinforcement Learning", "Security", "Training Techniques"]
short_authors: Li et al.
---
Large language models have recently evolved from fluent text generation to advanced reasoning across diverse domains, giving rise to reasoning language models. Among these domains, mathematical reasoning serves as a representative benchmark as it requires precise multi-step logic and abstract reasoning, which can be generalized to other tasks. While closed-source RLMs such as GPT-o3 demonstrate impressive reasoning capabilities, their proprietary nature limits transparency and reproducibility. Although many open-source projects aim to close this gap, most of them lack sufficient openness by omitting critical resources such as datasets and detailed training configurations, which hinders reproducibility. To contribute toward greater transparency in RLM development, we introduce the MiroMind-M1 series, a set of fully open-source RLMs built on the Qwen-2.5 backbone that match or exceed the performance of existing open-source RLMs. Specifically, our models are trained in two stages: SFT on a carefully curated corpus of 719K math-reasoning problems with verified CoT trajectories, followed by RLVR on 62K challenging and verifiable problems. To enhance the robustness and efficiency of the RLVR process, we introduce Context-Aware Multi-Stage Policy Optimization, an algorithm that integrates length-progressive training with an adaptive repetition penalty to encourage context-aware RL training. Our model achieves state-of-the-art or competitive performance and superior token efficiency among Qwen-2.5-based open-source 7B and 32B models on the AIME24, AIME25, and MATH benchmarks. To facilitate reproducibility, we release the complete stack: models (MiroMind-M1-SFT-7B, MiroMind-M1-RL-7B, MiroMind-M1-RL-32B); datasets (MiroMind-M1-SFT-719K, MiroMind-M1-RL-62K); and all training and evaluation configurations. We hope these resources will support further research and foster community advancement.

https://huggingface.co/discussions/paper/687eece933947f780d9b4a68