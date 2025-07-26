---
layout: publication
title: 'Adacot: Pareto-optimal Adaptive Chain-of-thought Triggering Via Reinforcement
  Learning'
authors: Chenwei Lou, Zewei Sun, Xinnian Liang, Meng Qu, Wei Shen, Wenqi Wang, Yuntao
  Li, Qingping Yang, Shuangzhi Wu
conference: No Venue
year: 2025
bibkey: lou2025adacot
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.11896'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Lou et al.
---
Large Language Models (LLMs) have demonstrated remarkable capabilities but often face challenges with tasks requiring sophisticated reasoning. While Chain-of-Thought (CoT) prompting significantly enhances reasoning, it indiscriminately generates lengthy reasoning steps for all queries, leading to substantial computational costs and inefficiency, especially for simpler inputs. To address this critical issue, we introduce AdaCoT (Adaptive Chain-of-Thought), a novel framework enabling LLMs to adaptively decide when to invoke CoT. AdaCoT framed adaptive reasoning as a Pareto optimization problem that seeks to balance model performance with the costs associated with CoT invocation (both frequency and computational overhead). We propose a reinforcement learning (RL) based method, specifically utilizing Proximal Policy Optimization (PPO), to dynamically control the CoT triggering decision boundary by adjusting penalty coefficients, thereby allowing the model to determine CoT necessity based on implicit query complexity. A key technical contribution is Selective Loss Masking (SLM), designed to counteract decision boundary collapse during multi-stage RL training, ensuring robust and stable adaptive triggering. Experimental results demonstrate that AdaCoT successfully navigates the Pareto frontier, achieving substantial reductions in CoT usage for queries not requiring elaborate reasoning. For instance, on our production traffic testset, AdaCoT reduced CoT triggering rates to as low as 3.18% and decreased average response tokens by 69.06%, while maintaining high performance on complex tasks.

https://huggingface.co/discussions/paper/682bf60725f785dbadfb3e32