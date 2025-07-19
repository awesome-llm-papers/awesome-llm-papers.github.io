---
layout: publication
title: Prompt Tuning With Diffusion For Few-shot Pre-trained Policy Generalization
authors: Hu et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: hu2024prompt
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.01168'}]
tags: [Merging, Prompting, Tools, Training Techniques, Efficiency And Optimization,
  Fine Tuning, ACL, Agentic, Few Shot, RAG, Reinforcement Learning]
---
Offline reinforcement learning (RL) methods harness previous experiences to
derive an optimal policy, forming the foundation for pre-trained large-scale
models (PLMs). When encountering tasks not seen before, PLMs often utilize
several expert trajectories as prompts to expedite their adaptation to new
requirements. Though a range of prompt-tuning methods have been proposed to
enhance the quality of prompts, these methods often face optimization
restrictions due to prompt initialization, which can significantly constrain
the exploration domain and potentially lead to suboptimal solutions. To
eliminate the reliance on the initial prompt, we shift our perspective towards
the generative model, framing the prompt-tuning process as a form of
conditional generative modeling, where prompts are generated from random noise.
Our innovation, the Prompt Diffuser, leverages a conditional diffusion model to
produce prompts of exceptional quality. Central to our framework is the
approach to trajectory reconstruction and the meticulous integration of
downstream task guidance during the training phase. Further experimental
results underscore the potency of the Prompt Diffuser as a robust and effective
tool for the prompt-tuning process, demonstrating strong performance in the
meta-RL tasks.