---
layout: publication
title: 'Augmented Language Models: A Survey'
authors: "Gr\xE9goire Mialon et al."
conference: Arxiv
year: 2023
citations: 118
bibkey: mialon2023augmented
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2302.07842v1'}]
tags: [RAG, Tools, Interpretability and Explainability, Survey Paper, Language Modeling]
---
This survey reviews works in which language models (LMs) are augmented with
reasoning skills and the ability to use tools. The former is defined as
decomposing a potentially complex task into simpler subtasks while the latter
consists in calling external modules such as a code interpreter. LMs can
leverage these augmentations separately or in combination via heuristics, or
learn to do so from demonstrations. While adhering to a standard missing tokens
prediction objective, such augmented LMs can use various, possibly
non-parametric external modules to expand their context processing ability,
thus departing from the pure language modeling paradigm. We therefore refer to
them as Augmented Language Models (ALMs). The missing token objective allows
ALMs to learn to reason, use tools, and even act, while still performing
standard natural language tasks and even outperforming most regular LMs on
several benchmarks. In this work, after reviewing current advance in ALMs, we
conclude that this new research direction has the potential to address common
limitations of traditional LMs such as interpretability, consistency, and
scalability issues.