---
layout: publication
title: 'Direct Nash Optimization: Teaching Language Models To Self-improve With General
  Preferences'
authors: Corby Rosset, Ching-an Cheng, Arindam Mitra, Michael Santacroce, Ahmed Awadallah,
  Tengyang Xie
conference: No Venue
year: 2024
bibkey: rosset2024direct
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.03715'}]
tags: ["Efficiency", "Model Architecture", "Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Rosset et al.
---
This paper studies post-training large language models (LLMs) using preference feedback from a powerful oracle to help a model iteratively improve over itself. The typical approach for post-training LLMs involves Reinforcement Learning from Human Feedback (RLHF), which traditionally separates reward learning and subsequent policy optimization. However, such a reward maximization approach is limited by the nature of "point-wise" rewards (such as Bradley-Terry model), which fails to express complex intransitive or cyclic preference relations. While advances on RLHF show reward learning and policy optimization can be merged into a single contrastive objective for stability, they yet still remain tethered to the reward maximization framework. Recently, a new wave of research sidesteps the reward maximization presumptions in favor of directly optimizing over "pair-wise" or general preferences. In this paper, we introduce Direct Nash Optimization (DNO), a provable and scalable algorithm that marries the simplicity and stability of contrastive learning with theoretical generality from optimizing general preferences. Because DNO is a batched on-policy algorithm using a regression-based objective, its implementation is straightforward and efficient. Moreover, DNO enjoys monotonic improvement across iterations that help it improve even over a strong teacher (such as GPT-4). In our experiments, a resulting 7B parameter Orca-2.5 model aligned by DNO achieves the state-of-the-art win-rate against GPT-4-Turbo of 33% on AlpacaEval 2.0 (even after controlling for response length), an absolute gain of 26% (7% to 33%) over the initializing model. It outperforms models with far more parameters, including Mistral Large, Self-Rewarding LM (70B parameters), and older versions of GPT-4.

https://huggingface.co/discussions/paper/66135071174b378a723d9822