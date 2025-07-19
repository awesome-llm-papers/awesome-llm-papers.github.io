---
layout: publication
title: Learning To Generate Prompts For Dialogue Generation Through Reinforcement
  Learning
authors: Su et al.
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: su2022learning
citations: 441
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.03931'}]
tags: [Prompting, Training Techniques, Agentic, EMNLP, Reinforcement Learning]
---
Much literature has shown that prompt-based learning is an efficient method
to make use of the large pre-trained language model. Recent works also exhibit
the possibility of steering a chatbot's output by plugging in an appropriate
prompt. Gradient-based methods are often used to perturb the prompts. However,
some language models are not even available to the public. In this work, we
first explored the combination of prompting and reinforcement learning (RL) to
steer models' generation without accessing any of the models' parameters.
Second, to reduce the training effort and enhance the generalizability to the
unseen task, we apply multi-task learning to make the model learn to generalize
to new tasks better. The experiment results show that our proposed method can
successfully control several state-of-the-art (SOTA) dialogue models without
accessing their parameters. Furthermore, the model demonstrates the strong
ability to quickly adapt to an unseen task in fewer steps than the baseline
model.