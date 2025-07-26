---
layout: publication
title: 'TTRL: Test-time Reinforcement Learning'
authors: Yuxin Zuo, Kaiyan Zhang, Shang Qu, Li Sheng, Xuekai Zhu, Biqing Qi, Youbang
  Sun, Ganqu Cui, Ning Ding, Bowen Zhou
conference: No Venue
year: 2025
bibkey: zuo2025ttrl
additional_links: [{name: Code, url: 'https://github.com/PRIME-RL/TTRL'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2504.16084'}]
tags: ["Has Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Zuo et al.
---
This paper investigates Reinforcement Learning (RL) on data without explicit labels for reasoning tasks in Large Language Models (LLMs). The core challenge of the problem is reward estimation during inference while not having access to ground-truth information. While this setting appears elusive, we find that common practices in Test-Time Scaling (TTS), such as majority voting, yield surprisingly effective rewards suitable for driving RL training. In this work, we introduce Test-Time Reinforcement Learning (TTRL), a novel method for training LLMs using RL on unlabeled data. TTRL enables self-evolution of LLMs by utilizing the priors in the pre-trained models. Our experiments demonstrate that TTRL consistently improves performance across a variety of tasks and models. Notably, TTRL boosts the pass@1 performance of Qwen-2.5-Math-7B by approximately 159% on the AIME 2024 with only unlabeled test data. Furthermore, although TTRL is only supervised by the Maj@N metric, TTRL has demonstrated performance to consistently surpass the upper limit of the initial model, and approach the performance of models trained directly on test data with ground-truth labels. Our experimental findings validate the general effectiveness of TTRL across various tasks, and highlight TTRL's potential for broader tasks and domains. GitHub: https://github.com/PRIME-RL/TTRL

https://huggingface.co/discussions/paper/6808558b07e80b69b2e351f3