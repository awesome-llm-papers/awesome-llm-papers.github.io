---
layout: publication
title: 'Self-attention Attribution: Interpreting Information Interactions Inside Transformer'
authors: Yaru Hao, Li Dong, Furu Wei, Ke Xu
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: hao2020self
citations: 123
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.11207'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Hao et al.
---
The great success of Transformer-based models benefits from the powerful
multi-head self-attention mechanism, which learns token dependencies and
encodes contextual information from the input. Prior work strives to attribute
model decisions to individual input features with different saliency measures,
but they fail to explain how these input features interact with each other to
reach predictions. In this paper, we propose a self-attention attribution
method to interpret the information interactions inside Transformer. We take
BERT as an example to conduct extensive studies. Firstly, we apply
self-attention attribution to identify the important attention heads, while
others can be pruned with marginal performance degradation. Furthermore, we
extract the most salient dependencies in each layer to construct an attribution
tree, which reveals the hierarchical interactions inside Transformer. Finally,
we show that the attribution results can be used as adversarial patterns to
implement non-targeted attacks towards BERT.