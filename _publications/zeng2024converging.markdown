---
layout: publication
title: 'Converging To A Lingua Franca: Evolution Of Linguistic Regions And Semantics
  Alignment In Multilingual Large Language Models'
authors: Zeng et al.
conference: The Modern Language Journal
year: 2024
bibkey: zeng2024converging
citations: 329
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.11718'}]
tags: [Reinforcement Learning, Training Techniques]
---
Large language models (LLMs) have demonstrated remarkable performance,
particularly in multilingual contexts. While recent studies suggest that LLMs
can transfer skills learned in one language to others, the internal mechanisms
behind this ability remain unclear. We observed that the neuron activation
patterns of LLMs exhibit similarities when processing the same language,
revealing the existence and location of key linguistic regions. Additionally,
we found that neuron activation patterns are similar when processing sentences
with the same semantic meaning in different languages. This indicates that LLMs
map semantically identical inputs from different languages into a "Lingua
Franca", a common semantic latent space that allows for consistent processing
across languages. This semantic alignment becomes more pronounced with training
and increased model size, resulting in a more language-agnostic activation
pattern. Moreover, we found that key linguistic neurons are concentrated in the
first and last layers of LLMs, becoming denser in the first layers as training
progresses. Experiments on BLOOM and LLaMA2 support these findings,
highlighting the structural evolution of multilingual LLMs during training and
scaling up. This paper provides insights into the internal workings of LLMs,
offering a foundation for future improvements in their cross-lingual
capabilities.