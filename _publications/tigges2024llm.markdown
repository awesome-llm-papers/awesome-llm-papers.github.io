---
layout: publication
title: LLM Circuit Analyses Are Consistent Across Training And Scale
authors: Tigges et al.
conference: PLOS ONE
year: 2024
bibkey: tigges2024llm
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.10827'}]
tags: [Training Techniques, Attention Mechanism, Alt, Model Architecture, Reinforcement
    Learning]
---
Most currently deployed large language models (LLMs) undergo continuous
training or additional finetuning. By contrast, most research into LLMs'
internal mechanisms focuses on models at one snapshot in time (the end of
pre-training), raising the question of whether their results generalize to
real-world settings. Existing studies of mechanisms over time focus on
encoder-only or toy models, which differ significantly from most deployed
models. In this study, we track how model mechanisms, operationalized as
circuits, emerge and evolve across 300 billion tokens of training in
decoder-only LLMs, in models ranging from 70 million to 2.8 billion parameters.
We find that task abilities and the functional components that support them
emerge consistently at similar token counts across scale. Moreover, although
such components may be implemented by different attention heads over time, the
overarching algorithm that they implement remains. Surprisingly, both these
algorithms and the types of components involved therein can replicate across
model scale. These results suggest that circuit analyses conducted on small
models at the end of pre-training can provide insights that still apply after
additional pre-training and over model scale.