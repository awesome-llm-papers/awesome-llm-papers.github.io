---
layout: publication
title: Reinforcement Learning With Verifiable Rewards Implicitly Incentivizes Correct
  Reasoning In Base Llms
authors: Xumeng Wen, Zihan Liu, Shun Zheng, Zhijian Xu, Shengyu Ye, Zhirong Wu, Xiao
  Liang, Yang Wang, Junjie Li, Ziming Miao, Jiang Bian, Mao Yang
conference: No Venue
year: 2025
bibkey: wen2025reinforcement
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.14245'}]
tags: ["Reinforcement Learning"]
short_authors: Wen et al.
---
Reinforcement Learning with Verifiable Rewards (RLVR) has emerged as a promising paradigm for advancing the reasoning capabilities of Large Language Models (LLMs). However, a critical paradox clouds its efficacy: RLVR-tuned models often underperform their base models on the Pass@K metric for solution-finding, leading to the hypothesis that RLVR merely re-weights existing reasoning paths at the cost of reasoning diversity. In this work, we resolve this contradiction by identifying the source of the problem: the Pass@K metric itself is a flawed measure of reasoning, as it credits correct final answers that probably arise from inaccurate or incomplete chains of thought (CoTs). To address this, we introduce a more precise evaluation metric, CoT-Pass@K, which mandates that both the reasoning path and the final answer be correct. We provide a new theoretical foundation that formalizes how RLVR, unlike traditional RL, is uniquely structured to incentivize logical integrity. Our empirical results are supportive: using CoT-Pass@K, we observe that RLVR can incentivize the generalization of correct reasoning for all values of K. Furthermore, by analyzing the training dynamics, we find that this enhanced reasoning capability emerges early in the training process and smoothly generalizes. Our work provides a clear perspective on the role of RLVR, offers a more reliable method for its evaluation, and confirms its potential to genuinely advance machine reasoning.

https://huggingface.co/discussions/paper/68521c2a0164cd1316710477