---
layout: publication
title: 'R1-reward: Training Multimodal Reward Model Through Stable Reinforcement Learning'
authors: Zhang et al.
conference: Artificial Intelligence
year: 2025
bibkey: zhang2025r1
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.02835'}]
tags: [Training Techniques, Agentic, Evaluation, IJCAI, AISTATS, Reinforcement Learning,
  UAI, Fine Tuning, Multimodal Models, AAAI, Datasets]
---
Multimodal Reward Models (MRMs) play a crucial role in enhancing the performance of Multimodal Large Language Models (MLLMs). While recent advancements have primarily focused on improving the model structure and training data of MRMs, there has been limited exploration into the effectiveness of long-term reasoning capabilities for reward modeling and how to activate these capabilities in MRMs. In this paper, we explore how Reinforcement Learning (RL) can be used to improve reward modeling. Specifically, we reformulate the reward modeling problem as a rule-based RL task. However, we observe that directly applying existing RL algorithms, such as Reinforce++, to reward modeling often leads to training instability or even collapse due to the inherent limitations of these algorithms. To address this issue, we propose the StableReinforce algorithm, which refines the training loss, advantage estimation strategy, and reward design of existing RL methods. These refinements result in more stable training dynamics and superior performance. To facilitate MRM training, we collect 200K preference data from diverse datasets. Our reward model, R1-Reward, trained using the StableReinforce algorithm on this dataset, significantly improves performance on multimodal reward modeling benchmarks. Compared to previous SOTA models, R1-Reward achieves a \\(8.4%\\) improvement on the VL Reward-Bench and a \\(14.3%\\) improvement on the Multimodal Reward Bench. Moreover, with more inference compute, R1-Reward's performance is further enhanced, highlighting the potential of RL algorithms in optimizing MRMs.