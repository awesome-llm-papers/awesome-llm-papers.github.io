---
layout: publication
title: 'Truth In The Few: High-value Data Selection For Efficient Multi-modal Reasoning'
authors: Shenshen Li, Kaiyuan Deng, Lei Wang, Hao Yang, Chong Peng, Peng Yan, Fumin
  Shen, Heng Tao Shen, Xing Xu
conference: No Venue
year: 2025
bibkey: li2025truth
additional_links: [{name: Code, url: 'https://github.com/Leo-ssl/RAP'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6846ba9d3ec10bdd8ab4dbec'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2506.04755'}]
tags: ["Datasets", "Has Code"]
short_authors: Li et al.
---
While multi-modal large language models (MLLMs) have made significant progress in complex reasoning tasks via reinforcement learning, it is commonly believed that extensive training data is necessary for improving multi-modal reasoning ability, inevitably leading to data redundancy and substantial computational costs. However, can smaller high-value datasets match or outperform full corpora for multi-modal reasoning in MLLMs? In this work, we challenge this assumption through a key observation: meaningful multi-modal reasoning is triggered by only a sparse subset of training samples, termed cognitive samples, whereas the majority contribute marginally. Building on this insight, we propose a novel data selection paradigm termed Reasoning Activation Potential (RAP), which identifies cognitive samples by estimating each sample's potential to stimulate genuine multi-modal reasoning by two complementary estimators: 1) Causal Discrepancy Estimator (CDE) based on the potential outcome model principle, eliminates samples that overly rely on language priors by comparing outputs between multi-modal and text-only inputs; 2) Attention Confidence Estimator (ACE), which exploits token-level self-attention to discard samples dominated by irrelevant but over-emphasized tokens in intermediate reasoning stages. Moreover, we introduce a Difficulty-aware Replacement Module (DRM) to substitute trivial instances with cognitively challenging ones, thereby ensuring complexity for robust multi-modal reasoning. Experiments on six datasets show that our RAP method consistently achieves superior performance using only 9.3% of the training data, while reducing computational costs by over 43%. Our code is available at https://github.com/Leo-ssl/RAP.

https://huggingface.co/discussions/paper/6846ba9d3ec10bdd8ab4dbec