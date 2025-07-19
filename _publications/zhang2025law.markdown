---
layout: publication
title: 'The Law Of Knowledge Overshadowing: Towards Understanding, Predicting, And
  Preventing LLM Hallucination'
authors: Zhang et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2025
bibkey: zhang2025law
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.16143'}]
tags: [Tools, Training Techniques, ACL, EMNLP, Reinforcement Learning, Language Modeling]
---
Hallucination is a persistent challenge in large language models (LLMs),
where even with rigorous quality control, models often generate distorted
facts. This paradox, in which error generation continues despite high-quality
training data, calls for a deeper understanding of the underlying LLM
mechanisms. To address it, we propose a novel concept: knowledge overshadowing,
where model's dominant knowledge can obscure less prominent knowledge during
text generation, causing the model to fabricate inaccurate details. Building on
this idea, we introduce a novel framework to quantify factual hallucinations by
modeling knowledge overshadowing. Central to our approach is the log-linear
law, which predicts that the rate of factual hallucination increases linearly
with the logarithmic scale of (1) Knowledge Popularity, (2) Knowledge Length,
and (3) Model Size. The law provides a means to preemptively quantify
hallucinations, offering foresight into their occurrence even before model
training or inference. Built on overshadowing effect, we propose a new decoding
strategy CoDa, to mitigate hallucinations, which notably enhance model
factuality on Overshadow (27.9%), MemoTrap (13.1%) and NQ-Swap (18.3%). Our
findings not only deepen understandings of the underlying mechanisms behind
hallucinations but also provide actionable insights for developing more
predictable and controllable language models.