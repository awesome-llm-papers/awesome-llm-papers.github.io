---
layout: publication
title: 'Toward Evaluative Thinking: Meta Policy Optimization With Evolving Reward
  Models'
authors: Zae Myung Kim, Chanwoo Park, Vipul Raheja, Dongyeop Kang
conference: No Venue
year: 2025
bibkey: kim2025toward
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68119751ff0764f3840a7fc5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.20157'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Kim et al.
---
Reward-based alignment methods for large language models (LLMs) face two key limitations: vulnerability to reward hacking, where models exploit flaws in the reward signal; and reliance on brittle, labor-intensive prompt engineering when LLMs are used as reward models. We introduce Meta Policy Optimization (MPO), a framework that addresses these challenges by integrating a meta-reward model that dynamically refines the reward model's prompt throughout training. In MPO, the meta-reward model monitors the evolving training context and continuously adjusts the reward model's prompt to maintain high alignment, providing an adaptive reward signal that resists exploitation by the policy. This meta-learning approach promotes a more stable policy optimization, and greatly reduces the need for manual reward prompt design. It yields performance on par with or better than models guided by extensively hand-crafted reward prompts. Furthermore, we show that MPO maintains its effectiveness across diverse tasks, such as question answering and mathematical reasoning, without requiring specialized reward designs. Beyond standard RLAIF, MPO's meta-learning formulation is readily extensible to higher-level alignment frameworks. Overall, this method addresses theoretical and practical challenges in reward-based RL alignment for LLMs, paving the way for more robust and adaptable alignment strategies. The code and models will be publicly shared.

https://huggingface.co/discussions/paper/68119751ff0764f3840a7fc5