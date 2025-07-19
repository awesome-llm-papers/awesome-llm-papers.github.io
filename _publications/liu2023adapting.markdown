---
layout: publication
title: Adapting Transformer Language Models For Predictive Typing In Brain-computer
  Interfaces
authors: Liu Shijia, Smith David A.
conference: 'Radiology: Artificial Intelligence'
year: 2023
bibkey: liu2023adapting
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.03819'}]
tags: [Alt, Model Architecture, Transformer, GPT]
---
Brain-computer interfaces (BCI) are an important mode of alternative and
augmentative communication for many people. Unlike keyboards, many BCI systems
do not display even the 26 letters of English at one time, let alone all the
symbols in more complex systems. Using language models to make character-level
predictions, therefore, can greatly speed up BCI typing (Ghosh and Kristensson,
2017). While most existing BCI systems employ character n-gram models or no LM
at all, this paper adapts several wordpiece-level Transformer LMs to make
character predictions and evaluates them on typing tasks. GPT-2 fares best on
clean text, but different LMs react differently to noisy histories. We further
analyze the effect of character positions in a word and context lengths.