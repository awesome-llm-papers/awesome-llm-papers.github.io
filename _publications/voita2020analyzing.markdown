---
layout: publication
title: Analyzing The Source And Target Contributions To Predictions In Neural Machine
  Translation
authors: Voita Elena, Sennrich Rico, Titov Ivan
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2020
bibkey: voita2020analyzing
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.10907'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, Reinforcement Learning]
---
In Neural Machine Translation (and, more generally, conditional language
modeling), the generation of a target token is influenced by two types of
context: the source and the prefix of the target sequence. While many attempts
to understand the internal workings of NMT models have been made, none of them
explicitly evaluates relative source and target contributions to a generation
decision. We argue that this relative contribution can be evaluated by adopting
a variant of Layerwise Relevance Propagation (LRP). Its underlying
'conservation principle' makes relevance propagation unique: differently from
other methods, it evaluates not an abstract quantity reflecting token
importance, but the proportion of each token's influence. We extend LRP to the
Transformer and conduct an analysis of NMT models which explicitly evaluates
the source and target relative contributions to the generation process. We
analyze changes in these contributions when conditioning on different types of
prefixes, when varying the training objective or the amount of training data,
and during the training process. We find that models trained with more data
tend to rely on source information more and to have more sharp token
contributions; the training process is non-monotonic with several stages of
different nature.