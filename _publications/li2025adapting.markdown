---
layout: publication
title: Adapting Pretrained Language Models For Citation Classification Via Self-supervised
  Contrastive Learning
authors: Li et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: li2025adapting
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.14471'}]
tags: [Training Techniques, Tools, Evaluation, Reinforcement Learning, Fine Tuning,
  AAAI, Datasets]
---
Citation classification, which identifies the intention behind academic citations, is pivotal for scholarly analysis. Previous works suggest fine-tuning pretrained language models (PLMs) on citation classification datasets, reaping the reward of the linguistic knowledge they gained during pretraining. However, directly fine-tuning for citation classification is challenging due to labeled data scarcity, contextual noise, and spurious keyphrase correlations. In this paper, we present a novel framework, Citss, that adapts the PLMs to overcome these challenges. Citss introduces self-supervised contrastive learning to alleviate data scarcity, and is equipped with two specialized strategies to obtain the contrastive pairs: sentence-level cropping, which enhances focus on target citations within long contexts, and keyphrase perturbation, which mitigates reliance on specific keyphrases. Compared with previous works that are only designed for encoder-based PLMs, Citss is carefully developed to be compatible with both encoder-based PLMs and decoder-based LLMs, to embrace the benefits of enlarged pretraining. Experiments with three benchmark datasets with both encoder-based PLMs and decoder-based LLMs demonstrate our superiority compared to the previous state of the art. Our code is available at: github.com/LITONG99/Citss