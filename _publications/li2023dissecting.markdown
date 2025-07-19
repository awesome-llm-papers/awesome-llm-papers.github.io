---
layout: publication
title: 'Dissecting Chain-of-thought: Compositionality Through In-context Filtering
  And Learning'
authors: Li et al.
conference: Mind &amp; Language
year: 2023
bibkey: li2023dissecting
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.18869'}]
tags: [Training Techniques, Attention Mechanism, In Context Learning, Transformer,
  Model Architecture, Reinforcement Learning]
---
Chain-of-thought (CoT) is a method that enables language models to handle
complex reasoning tasks by decomposing them into simpler steps. Despite its
success, the underlying mechanics of CoT are not yet fully understood. In an
attempt to shed light on this, our study investigates the impact of CoT on the
ability of transformers to in-context learn a simple to study, yet general
family of compositional functions: multi-layer perceptrons (MLPs). In this
setting, we find that the success of CoT can be attributed to breaking down
in-context learning of a compositional function into two distinct phases:
focusing on and filtering data related to each step of the composition and
in-context learning the single-step composition function. Through both
experimental and theoretical evidence, we demonstrate how CoT significantly
reduces the sample complexity of in-context learning (ICL) and facilitates the
learning of complex functions that non-CoT methods struggle with. Furthermore,
we illustrate how transformers can transition from vanilla in-context learning
to mastering a compositional function with CoT by simply incorporating
additional layers that perform the necessary data-filtering for CoT via the
attention mechanism. In addition to these test-time benefits, we show CoT helps
accelerate pretraining by learning shortcuts to represent complex functions and
filtering plays an important role in this process. These findings collectively
provide insights into the mechanics of CoT, inviting further investigation of
its role in complex reasoning tasks.