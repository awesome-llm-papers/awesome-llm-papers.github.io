---
layout: publication
title: Multimodal Knowledge Alignment With Reinforcement Learning
authors: Youngjae Yu et al.
conference: Arxiv
year: 2022
citations: 16
bibkey: yu2022multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12630'}]
tags: [Reinforcement Learning, Multimodal Models, Agentic, Efficiency and Optimization,
  Training Techniques, Evaluation]
---
Large language models readily adapt to novel settings, even without
task-specific training data. Can their zero-shot capacity be extended to
multimodal inputs? In this work, we propose ESPER which extends language-only
zero-shot models to unseen multimodal tasks, like image and audio captioning.
Our key novelty is to use reinforcement learning to align multimodal inputs to
language model generations without direct supervision: for example, in the
image case our reward optimization relies only on cosine similarity derived
from CLIP, and thus requires no additional explicitly paired (image, caption)
data. Because the parameters of the language model are left unchanged, the
model maintains its capacity for zero-shot generalization. Experiments
demonstrate that ESPER outperforms baselines and prior work on a variety of
zero-shot tasks; these include a new benchmark we collect+release, ESP dataset,
which tasks models with generating several diversely-styled captions for each
image.