---
layout: publication
title: 'Blackvip: Black-box Visual Prompting For Robust Transfer Learning'
authors: Changdae Oh et al.
conference: Arxiv
year: 2023
citations: 20
bibkey: oh2023black
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.14773'}, {name: Code,
    url: 'https://github.com/changdaeoh/BlackVIP'}]
tags: [Training Techniques, Fine-Tuning, Few-Shot, Tools, Reinforcement Learning,
  Attention Mechanism, Has Code, Applications, Security, Prompting, Model Architecture]
---
With the surge of large-scale pre-trained models (PTMs), fine-tuning these
models to numerous downstream tasks becomes a crucial problem. Consequently,
parameter efficient transfer learning (PETL) of large models has grasped huge
attention. While recent PETL methods showcase impressive performance, they rely
on optimistic assumptions: 1) the entire parameter set of a PTM is available,
and 2) a sufficiently large memory capacity for the fine-tuning is equipped.
However, in most real-world applications, PTMs are served as a black-box API or
proprietary software without explicit parameter accessibility. Besides, it is
hard to meet a large memory requirement for modern PTMs. In this work, we
propose black-box visual prompting (BlackVIP), which efficiently adapts the
PTMs without knowledge about model architectures and parameters. BlackVIP has
two components; 1) Coordinator and 2) simultaneous perturbation stochastic
approximation with gradient correction (SPSA-GC). The Coordinator designs
input-dependent image-shaped visual prompts, which improves few-shot adaptation
and robustness on distribution/location shift. SPSA-GC efficiently estimates
the gradient of a target model to update Coordinator. Extensive experiments on
16 datasets demonstrate that BlackVIP enables robust adaptation to diverse
domains without accessing PTMs' parameters, with minimal memory requirements.
Code: https://github.com/changdaeoh/BlackVIP