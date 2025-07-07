---
layout: publication
title: Personalized Prompt For Sequential Recommendation
authors: Yiqing Wu et al.
conference: Arxiv
year: 2022
citations: 17
bibkey: wu2022personalized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.09666'}]
tags: [Training Techniques, Pre-Training, Few-Shot, Tools, Fine-Tuning, Prompting]
---
Pre-training models have shown their power in sequential recommendation.
Recently, prompt has been widely explored and verified for tuning in NLP
pre-training, which could help to more effectively and efficiently extract
useful knowledge from pre-training models for downstream tasks, especially in
cold-start scenarios. However, it is challenging to bring prompt-tuning from
NLP to recommendation, since the tokens in recommendation (i.e., items) do not
have explicit explainable semantics, and the sequence modeling should be
personalized. In this work, we first introduces prompt to recommendation and
propose a novel Personalized prompt-based recommendation (PPR) framework for
cold-start recommendation. Specifically, we build the personalized soft prefix
prompt via a prompt generator based on user profiles and enable a sufficient
training of prompts via a prompt-oriented contrastive learning with both
prompt- and behavior-based augmentations. We conduct extensive evaluations on
various tasks. In both few-shot and zero-shot recommendation, PPR models
achieve significant improvements over baselines on various metrics in three
large-scale open datasets. We also conduct ablation tests and sparsity analysis
for a better understanding of PPR. Moreover, We further verify PPR's
universality on different pre-training models, and conduct explorations on
PPR's other promising downstream tasks including cross-domain recommendation
and user profile prediction.