---
layout: publication
title: Visual Abductive Reasoning
authors: Liang et al.
conference: Philosophy of Science
year: 2022
bibkey: liang2022visual
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.14040'}]
tags: [Interpretability And Explainability, Alt, Evaluation, Transformer, Model Architecture,
  Datasets]
---
Abductive reasoning seeks the likeliest possible explanation for partial
observations. Although abduction is frequently employed in human daily
reasoning, it is rarely explored in computer vision literature. In this paper,
we propose a new task and dataset, Visual Abductive Reasoning (VAR), for
examining abductive reasoning ability of machine intelligence in everyday
visual situations. Given an incomplete set of visual events, AI systems are
required to not only describe what is observed, but also infer the hypothesis
that can best explain the visual premise. Based on our large-scale VAR dataset,
we devise a strong baseline model, Reasoner (causal-and-cascaded reasoning
Transformer). First, to capture the causal structure of the observations, a
contextualized directional position embedding strategy is adopted in the
encoder, that yields discriminative representations for the premise and
hypothesis. Then, multiple decoders are cascaded to generate and progressively
refine the premise and hypothesis sentences. The prediction scores of the
sentences are used to guide cross-sentence information flow in the cascaded
reasoning procedure. Our VAR benchmarking results show that Reasoner surpasses
many famous video-language models, while still being far behind human
performance. This work is expected to foster future efforts in the
reasoning-beyond-observation paradigm.