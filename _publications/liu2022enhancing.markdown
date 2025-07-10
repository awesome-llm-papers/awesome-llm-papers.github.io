---
layout: publication
title: 'Matcha: Enhancing Visual Language Pretraining With Math Reasoning And Chart
  Derendering'
authors: Fangyu Liu et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
citations: 15
bibkey: liu2022enhancing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.09662'}]
tags: [Language Modeling, Reinforcement Learning, Multimodal Models, Training Techniques,
  Evaluation]
---
Visual language data such as plots, charts, and infographics are ubiquitous
in the human world. However, state-of-the-art vision-language models do not
perform well on these data. We propose MatCha (Math reasoning and Chart
derendering pretraining) to enhance visual language models' capabilities in
jointly modeling charts/plots and language data. Specifically, we propose
several pretraining tasks that cover plot deconstruction and numerical
reasoning which are the key capabilities in visual language modeling.
  We perform the MatCha pretraining starting from Pix2Struct, a recently
proposed image-to-text visual language model. On standard benchmarks such as
PlotQA and ChartQA, the MatCha model outperforms state-of-the-art methods by as
much as nearly 20%. We also examine how well MatCha pretraining transfers to
domains such as screenshots, textbook diagrams, and document figures and
observe overall improvement, verifying the usefulness of MatCha pretraining on
broader visual language tasks.