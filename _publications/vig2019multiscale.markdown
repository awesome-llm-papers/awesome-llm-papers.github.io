---
layout: publication
title: A Multiscale Visualization Of Attention In The Transformer Model
authors: Jesse Vig
conference: 'Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics: System Demonstrations'
year: 2019
bibkey: vig2019multiscale
citations: 453
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.05714'}]
tags: ["Model Architecture"]
short_authors: Jesse Vig
---
The Transformer is a sequence model that forgoes traditional recurrent
architectures in favor of a fully attention-based approach. Besides improving
performance, an advantage of using attention is that it can also help to
interpret a model by showing how the model assigns weight to different input
elements. However, the multi-layer, multi-head attention mechanism in the
Transformer model can be difficult to decipher. To make the model more
accessible, we introduce an open-source tool that visualizes attention at
multiple scales, each of which provides a unique perspective on the attention
mechanism. We demonstrate the tool on BERT and OpenAI GPT-2 and present three
example use cases: detecting model bias, locating relevant attention heads, and
linking neurons to model behavior.