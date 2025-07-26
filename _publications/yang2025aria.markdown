---
layout: publication
title: 'ARIA: Training Language Agents With Intention-driven Reward Aggregation'
authors: Ruihan Yang, Yikai Zhang, Aili Chen, Xintao Wang, Siyu Yuan, Jiangjie Chen,
  Deqing Yang, Yanghua Xiao
conference: No Venue
year: 2025
bibkey: yang2025aria
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.00539'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Yang et al.
---
Large language models (LLMs) have enabled agents to perform complex reasoning and decision-making through free-form language interactions. However, in open-ended language action environments (e.g., negotiation or question-asking games), the action space can be formulated as a joint distribution over tokens, resulting in an exponentially large action space. Sampling actions in such a space can lead to extreme reward sparsity, which brings large reward variance, hindering effective reinforcement learning (RL). To address this, we propose ARIA, a method that Aggregates Rewards in Intention space to enable efficient and effective language Agents training. ARIA aims to project natural language actions from the high-dimensional joint token distribution space into a low-dimensional intention space, where semantically similar actions are clustered and assigned shared rewards. This intention-aware reward aggregation reduces reward variance by densifying reward signals, fostering better policy optimization. Extensive experiments demonstrate that ARIA not only significantly reduces policy gradient variance, but also delivers substantial performance gains of an average of 9.95% across four downstream tasks, consistently outperforming offline and online RL baselines.

https://huggingface.co/discussions/paper/683e76ca7a0996f979e728e0