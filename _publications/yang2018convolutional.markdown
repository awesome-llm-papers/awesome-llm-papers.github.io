---
layout: publication
title: Convolutional Self-attention Network
authors: Baosong Yang, Longyue Wang, Derek F. Wong, Lidia S. Chao, Zhaopeng Tu
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: yang2018convolutional
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.13320'}]
tags: ["Model Architecture"]
short_authors: Yang et al.
---
Self-attention network (SAN) has recently attracted increasing interest due
to its fully parallelized computation and flexibility in modeling dependencies.
It can be further enhanced with multi-headed attention mechanism by allowing
the model to jointly attend to information from different representation
subspaces at different positions (Vaswani et al., 2017). In this work, we
propose a novel convolutional self-attention network (CSAN), which offers SAN
the abilities to 1) capture neighboring dependencies, and 2) model the
interaction between multiple attention heads. Experimental results on WMT14
English-to-German translation task demonstrate that the proposed approach
outperforms both the strong Transformer baseline and other existing works on
enhancing the locality of SAN. Comparing with previous work, our model does not
introduce any new parameters.