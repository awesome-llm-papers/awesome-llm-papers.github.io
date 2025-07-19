---
layout: publication
title: Seeing The Arrow Of Time In Large Multimodal Models
authors: Xue Zihui, Luo Mi, Grauman Kristen
conference: 2014 IEEE Conference on Computer Vision and Pattern Recognition
year: 2025
bibkey: xue2025seeing
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.03340'}]
tags: [RAG, Training Techniques, Agentic, Tools, CVPR, Evaluation, Reinforcement Learning,
  Multimodal Models, Datasets]
---
The Arrow of Time (AoT)-time's irreversible flow shaping physical events-is fundamental to video comprehension, yet remains a significant challenge for modern large multimodal models (LMMs). Current LMMs struggle to perceive and utilize temporal directionality in video when responding to language queries, obstructing deeper temporal understanding. We tackle this deficiency by first providing a critical analysis of existing benchmarks and models. We then introduce ArrowRL, a reinforcement learning (RL)-based training strategy with an innovative reverse reward that instills AoT awareness by encouraging divergent video interpretations between forward and reversed visual frames. For rigorous evaluation, we additionally develop AoTBench, a new multi-faceted benchmark probing temporally challenging questions. Experiments show ArrowRL greatly advances temporal perception: it not only achieves substantial improvements on our challenging AoTBench but also demonstrably boosts performance on standard video question answering (VQA) benchmarks (with peak accuracy gains reaching over 20% and 10% respectively). This validates ArrowRL's effectiveness and highlights the critical need for dedicated AoT understanding in LMMs.