---
layout: publication
title: Injecting Numerical Reasoning Skills Into Language Models
authors: Mor Geva, Ankit Gupta, Jonathan Berant
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: geva2020injecting
citations: 161
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.04487'}]
tags: ["Training Techniques"]
short_authors: Mor Geva, Ankit Gupta, Jonathan Berant
---
Large pre-trained language models (LMs) are known to encode substantial
amounts of linguistic information. However, high-level reasoning skills, such
as numerical reasoning, are difficult to learn from a language-modeling
objective only. Consequently, existing models for numerical reasoning have used
specialized architectures with limited flexibility. In this work, we show that
numerical reasoning is amenable to automatic data generation, and thus one can
inject this skill into pre-trained LMs, by generating large amounts of data,
and training in a multi-task setup. We show that pre-training our model,
GenBERT, on this data, dramatically improves performance on DROP (49.3
\\(\rightarrow\\) 72.3 F1), reaching performance that matches state-of-the-art
models of comparable size, while using a simple and general-purpose
encoder-decoder architecture. Moreover, GenBERT generalizes well to math word
problem datasets, while maintaining high performance on standard RC tasks. Our
approach provides a general recipe for injecting skills into large pre-trained
LMs, whenever the skill is amenable to automatic data augmentation.