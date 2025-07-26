---
layout: publication
title: Hierarchically Structured Reinforcement Learning For Topically Coherent Visual
  Story Generation
authors: Qiuyuan Huang, Zhe Gan, Asli Celikyilmaz, Dapeng Wu, Jianfeng Wang, Xiaodong
  He
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: huang2018hierarchically
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.08191'}]
tags: ["AAAI", "Reinforcement Learning"]
short_authors: Huang et al.
---
We propose a hierarchically structured reinforcement learning approach to
address the challenges of planning for generating coherent multi-sentence
stories for the visual storytelling task. Within our framework, the task of
generating a story given a sequence of images is divided across a two-level
hierarchical decoder. The high-level decoder constructs a plan by generating a
semantic concept (i.e., topic) for each image in sequence. The low-level
decoder generates a sentence for each image using a semantic compositional
network, which effectively grounds the sentence generation conditioned on the
topic. The two decoders are jointly trained end-to-end using reinforcement
learning. We evaluate our model on the visual storytelling (VIST) dataset.
Empirical results from both automatic and human evaluations demonstrate that
the proposed hierarchically structured reinforced training achieves
significantly better performance compared to a strong flat deep reinforcement
learning baseline.