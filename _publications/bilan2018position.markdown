---
layout: publication
title: Position-aware Self-attention With Relative Positional Encodings For Slot Filling
authors: Bilan Ivan, Roth Benjamin
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: bilan2018position
citations: 337
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.03052'}]
tags: [Model Architecture, Evaluation, EMNLP, Transformer, Datasets, Attention Mechanism]
---
This paper describes how to apply self-attention with relative positional
encodings to the task of relation extraction. We propose to use the
self-attention encoder layer together with an additional position-aware
attention layer that takes into account positions of the query and the object
in the sentence. The self-attention encoder also uses a custom implementation
of relative positional encodings which allow each word in the sentence to take
into account its left and right context. The evaluation of the model is done on
the TACRED dataset. The proposed model relies only on attention (no recurrent
or convolutional layers are used), while improving performance w.r.t. the
previous state of the art.