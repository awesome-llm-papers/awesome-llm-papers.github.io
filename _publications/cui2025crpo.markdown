---
layout: publication
title: 'CRPO: Confidence-reward Driven Preference Optimization For Machine Translation'
authors: Cui et al.
conference: Proceedings of the 20th international conference on Computational Linguistics  -
  COLING '04
year: 2025
bibkey: cui2025crpo
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.13927'}]
tags: [Training Techniques, Alt, Agentic, COLING, Efficiency And Optimization, Reinforcement
    Learning, Fine Tuning]
---
Large language models (LLMs) have shown great potential in natural language
processing tasks, but their application to machine translation (MT) remains
challenging due to pretraining on English-centric data and the complexity of
reinforcement learning from human feedback (RLHF). Direct Preference
Optimization (DPO) has emerged as a simpler and more efficient alternative, but
its performance depends heavily on the quality of preference data. To address
this, we propose Confidence-Reward driven Preference Optimization (CRPO), a
novel method that combines reward scores with model confidence to improve data
selection for fine-tuning. CRPO selects challenging sentence pairs where the
model is uncertain or underperforms, leading to more effective learning. While
primarily designed for LLMs, CRPO also generalizes to encoder-decoder models
like NLLB, demonstrating its versatility. Empirical results show that CRPO
outperforms existing methods such as RS-DPO, RSO and MBR score in both
translation accuracy and data efficiency.