---
layout: publication
title: 'Reflect, Retry, Reward: Self-improving Llms Via Reinforcement Learning'
authors: Shelly Bensal, Umar Jamil, Christopher Bryant, Melisa Russak, Kiran Kamble,
  Dmytro Mozolevskyi, Muayad Ali, Waseem Alshikh
conference: No Venue
year: 2025
bibkey: bensal2025reflect
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.24726'}]
tags: ["Reinforcement Learning"]
short_authors: Bensal et al.
---
We explore a method for improving the performance of large language models through self-reflection and reinforcement learning. By incentivizing the model to generate better self-reflections when it answers incorrectly, we demonstrate that a model's ability to solve complex, verifiable tasks can be enhanced even when generating synthetic data is infeasible and only binary feedback is available. Our framework operates in two stages: first, upon failing a given task, the model generates a self-reflective commentary analyzing its previous attempt; second, the model is given another attempt at the task with the self-reflection in context. If the subsequent attempt succeeds, the tokens generated during the self-reflection phase are rewarded. Our experimental results show substantial performance gains across a variety of model architectures, as high as 34.7% improvement at math equation writing and 18.1% improvement at function calling. Notably, smaller fine-tuned models (1.5 billion to 7 billion parameters) outperform models in the same family that are 10 times larger. Our novel paradigm is thus an exciting pathway to more useful and reliable language models that can self-improve on challenging tasks with limited external feedback.

https://huggingface.co/discussions/paper/683ffca568402c738a947f7b