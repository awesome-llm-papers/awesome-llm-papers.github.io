---
layout: publication
title: Video Captioning With Multi-faceted Attention
authors: Xiang Long, Chuang Gan, Gerard de Melo
conference: Transactions of the Association for Computational Linguistics
year: 2018
bibkey: long2016video
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.00234'}]
tags: ["Model Architecture", "TACL"]
short_authors: Xiang Long, Chuang Gan, Gerard de Melo
---
Recently, video captioning has been attracting an increasing amount of
interest, due to its potential for improving accessibility and information
retrieval. While existing methods rely on different kinds of visual features
and model structures, they do not fully exploit relevant semantic information.
We present an extensible approach to jointly leverage several sorts of visual
features and semantic attributes. Our novel architecture builds on LSTMs for
sentence generation, with several attention layers and two multimodal layers.
The attention mechanism learns to automatically select the most salient visual
features or semantic attributes, and the multimodal layer yields overall
representations for the input and outputs of the sentence generation component.
Experimental results on the challenging MSVD and MSR-VTT datasets show that our
framework outperforms the state-of-the-art approaches, while ground truth based
semantic attributes are able to further elevate the output quality to a
near-human level.