---
layout: publication
title: 'SEAP: Training-free Sparse Expert Activation Pruning Unlock The Brainpower
  Of Large Language Models'
authors: Xun Liang, Hanyu Wang, Huayi Lai, Simin Niu, Shichao Song, Jiawei Yang, Jihao
  Zhao, Feiyu Xiong, Bo Tang, Zhiyu Li
conference: No Venue
year: 2025
bibkey: liang2025seap
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.07605'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Liang et al.
---
Large Language Models have achieved remarkable success across various natural language processing tasks, yet their high computational cost during inference remains a major bottleneck. This paper introduces Sparse Expert Activation Pruning (SEAP), a training-free pruning method that selectively retains task-relevant parameters to reduce inference overhead. Inspired by the clustering patterns of hidden states and activations in LLMs, SEAP identifies task-specific expert activation patterns and prunes the model while preserving task performance and enhancing computational efficiency. Experimental results demonstrate that SEAP significantly reduces computational overhead while maintaining competitive accuracy. Notably, at 50% pruning, SEAP surpasses both WandA and FLAP by over 20%, and at 20% pruning, it incurs only a 2.2% performance drop compared to the dense model. These findings highlight SEAP's scalability and effectiveness, making it a promising approach for optimizing large-scale LLMs.

https://huggingface.co/discussions/paper/67cfa0c2edb742caa35729dc