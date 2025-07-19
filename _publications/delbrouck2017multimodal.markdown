---
layout: publication
title: Multimodal Compact Bilinear Pooling For Multimodal Neural Machine Translation
authors: Delbrouck Jean-benoit, Dupont Stephane
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: delbrouck2017multimodal
citations: 883
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.08084'}]
tags: [Model Architecture, EMNLP, Transformer, Multimodal Models, Attention Mechanism]
---
In state-of-the-art Neural Machine Translation, an attention mechanism is
used during decoding to enhance the translation. At every step, the decoder
uses this mechanism to focus on different parts of the source sentence to
gather the most useful information before outputting its target word. Recently,
the effectiveness of the attention mechanism has also been explored for
multimodal tasks, where it becomes possible to focus both on sentence parts and
image regions. Approaches to pool two modalities usually include element-wise
product, sum or concatenation. In this paper, we evaluate the more advanced
Multimodal Compact Bilinear pooling method, which takes the outer product of
two vectors to combine the attention features for the two modalities. This has
been previously investigated for visual question answering. We try out this
approach for multimodal image caption translation and show improvements
compared to basic combination methods.