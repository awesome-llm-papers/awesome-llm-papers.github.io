---
layout: publication
title: Inference-time Scaling For Generalist Reward Modeling
authors: Liu et al.
conference: Nature Neuroscience
year: 2025
bibkey: liu2025inference
citations: 189
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.02495'}]
tags: [Training Techniques, Agentic, Evaluation, Ethics And Bias, Reinforcement Learning,
  Datasets]
---
Reinforcement learning (RL) has been widely adopted in post-training for
large language models (LLMs) at scale. Recently, the incentivization of
reasoning capabilities in LLMs from RL indicates that \\(\textit\{proper learning
methods could enable effective inference-time scalability\}\\). A key challenge of
RL is to obtain accurate reward signals for LLMs in various domains beyond
verifiable questions or artificial rules. In this work, we investigate how to
improve reward modeling (RM) with more inference compute for general queries,
i.e. the \\(\textbf\{inference-time scalability of generalist RM\}\\), and further,
how to improve the effectiveness of performance-compute scaling with proper
learning methods. For the RM approach, we adopt pointwise generative reward
modeling (GRM) to enable flexibility for different input types and potential
for inference-time scaling. For the learning method, we propose Self-Principled
Critique Tuning (SPCT) to foster scalable reward generation behaviors in GRMs
through online RL, to generate principles adaptively and critiques accurately,
resulting in \\(\textbf\{DeepSeek-GRM\}\\) models. Furthermore, for effective
inference-time scaling, we use parallel sampling to expand compute usage, and
introduce a meta RM to guide voting process for better scaling performance.
Empirically, we show that SPCT significantly improves the quality and
scalability of GRMs, outperforming existing methods and models in various RM
benchmarks without severe biases, and could achieve better performance compared
to training-time scaling. DeepSeek-GRM still meets challenges in some tasks,
which we believe can be addressed by future efforts in generalist reward
systems. The models will be released and open-sourced.