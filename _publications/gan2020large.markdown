---
layout: publication
title: Large-scale Adversarial Training For Vision-and-language Representation Learning
authors: Zhe Gan, Yen-chun Chen, Linjie Li, Chen Zhu, Yu Cheng, Jingjing Liu
conference: Arxiv
year: 2020
bibkey: gan2020large
citations: 270
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.06195'}]
tags: ["Training Techniques"]
short_authors: Gan et al.
---
We present VILLA, the first known effort on large-scale adversarial training
for vision-and-language (V+L) representation learning. VILLA consists of two
training stages: (i) task-agnostic adversarial pre-training; followed by (ii)
task-specific adversarial finetuning. Instead of adding adversarial
perturbations on image pixels and textual tokens, we propose to perform
adversarial training in the embedding space of each modality. To enable
large-scale training, we adopt the "free" adversarial training strategy, and
combine it with KL-divergence-based regularization to promote higher invariance
in the embedding space. We apply VILLA to current best-performing V+L models,
and achieve new state of the art on a wide range of tasks, including Visual
Question Answering, Visual Commonsense Reasoning, Image-Text Retrieval,
Referring Expression Comprehension, Visual Entailment, and NLVR2.