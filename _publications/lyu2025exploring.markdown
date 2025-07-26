---
layout: publication
title: Exploring The Limit Of Outcome Reward For Learning Mathematical Reasoning
authors: Chengqi Lyu, Songyang Gao, Yuzhe Gu, Wenwei Zhang, Jianfei Gao, Kuikun Liu,
  Ziyi Wang, Shuaibin Li, Qian Zhao, Haian Huang, Weihan Cao, Jiangning Liu, Hongwei
  Liu, Junnan Liu, Songyang Zhang, Dahua Lin, Kai Chen
conference: No Venue
year: 2025
bibkey: lyu2025exploring
additional_links: [{name: Code, url: 'https://github.com/InternLM/OREAL'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67aacd7f078cdf445284fa4b'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2502.06781'}]
tags: ["Reinforcement Learning"]
short_authors: Lyu et al.
---
Reasoning abilities, especially those for solving complex math problems, are crucial components of general intelligence. Recent advances by proprietary companies, such as o-series models of OpenAI, have made remarkable progress on reasoning tasks. However, the complete technical details remain unrevealed, and the techniques that are believed certainly to be adopted are only reinforcement learning (RL) and the long chain of thoughts. This paper proposes a new RL framework, termed OREAL, to pursue the performance limit that can be achieved through Outcome REwArd-based reinforcement Learning for mathematical reasoning tasks, where only binary outcome rewards are easily accessible. We theoretically prove that behavior cloning on positive trajectories from best-of-N (BoN) sampling is sufficient to learn the KL-regularized optimal policy in binary feedback environments. This formulation further implies that the rewards of negative samples should be reshaped to ensure the gradient consistency between positive and negative samples. To alleviate the long-existing difficulties brought by sparse rewards in RL, which are even exacerbated by the partial correctness of the long chain of thought for reasoning tasks, we further apply a token-level reward model to sample important tokens in reasoning trajectories for learning. With OREAL, for the first time, a 7B model can obtain 94.0 pass@1 accuracy on MATH-500 through RL, being on par with 32B models. OREAL-32B also surpasses previous 32B models trained by distillation with 95.0 pass@1 accuracy on MATH-500. Our investigation also indicates the importance of initial policy models and training queries for RL. Code, models, and data will be released to benefit future researchhttps://github.com/InternLM/OREAL.

https://huggingface.co/discussions/paper/67aacd7f078cdf445284fa4b