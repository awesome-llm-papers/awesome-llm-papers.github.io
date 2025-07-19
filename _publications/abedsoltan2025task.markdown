---
layout: publication
title: 'Task Generalization With Autoregressive Compositional Structure: Can Learning
  From \(D\) Tasks Generalize To \(D^{T}\) Tasks?'
authors: Abedsoltan et al.
conference: 2018 IEEE International Conference on Robotics and Automation (ICRA)
year: 2025
bibkey: abedsoltan2025task
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.08991'}]
tags: [ICRA, Training Techniques, GPT, Transformer, In Context Learning, Model Architecture]
---
Large language models (LLMs) exhibit remarkable task generalization, solving tasks they were never explicitly trained on with only a few demonstrations. This raises a fundamental question: When can learning from a small set of tasks generalize to a large task family? In this paper, we investigate task generalization through the lens of autoregressive compositional structure, where each task is a composition of \\(T\\) operations, and each operation is among a finite family of \\(D\\) subtasks. This yields a total class of size \\(D^T\\). We first show that generalization to all \\(D^T\\) tasks is theoretically achievable by training on only \\(\widetilde\{O\}(D)\\) tasks. Empirically, we demonstrate that Transformers achieve such exponential task generalization on sparse parity functions via In-context Learning (ICL) and chain-of-thought (CoT) reasoning. We further show generalization in arithmetic and translation, beyond parity functions.