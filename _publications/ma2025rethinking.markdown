---
layout: publication
title: 'Rethinking RL Scaling For Vision Language Models: A Transparent, From-scratch
  Framework And Comprehensive Evaluation Scheme'
authors: Yan Ma, Steffi Chern, Xuyang Shen, Yiran Zhong, Pengfei Liu
conference: No Venue
year: 2025
bibkey: ma2025rethinking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.02587'}]
tags: ["Reinforcement Learning"]
short_authors: Ma et al.
---
Reinforcement learning (RL) has recently shown strong potential in improving the reasoning capabilities of large language models and is now being actively extended to vision-language models (VLMs). However, existing RL applications in VLMs often rely on heavily engineered frameworks that hinder reproducibility and accessibility, while lacking standardized evaluation protocols, making it difficult to compare results or interpret training dynamics. This work introduces a transparent, from-scratch framework for RL in VLMs, offering a minimal yet functional four-step pipeline validated across multiple models and datasets. In addition, a standardized evaluation scheme is proposed to assess training dynamics and reflective behaviors. Extensive experiments on visual reasoning tasks uncover key empirical findings: response length is sensitive to random seeds, reflection correlates with output length, and RL consistently outperforms supervised fine-tuning (SFT) in generalization, even with high-quality data. These findings, together with the proposed framework, aim to establish a reproducible baseline and support broader engagement in RL-based VLM research.

https://huggingface.co/discussions/paper/67ef3f9904be7fba0c882772