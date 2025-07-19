---
layout: publication
title: Recurrent Stacking Of Layers For Compact Neural Machine Translation Models
authors: Dabre Raj, Fujita Atsushi
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: dabre2018recurrent
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.05353'}]
tags: [AAAI]
---
In neural machine translation (NMT), the most common practice is to stack a
number of recurrent or feed-forward layers in the encoder and the decoder. As a
result, the addition of each new layer improves the translation quality
significantly. However, this also leads to a significant increase in the number
of parameters. In this paper, we propose to share parameters across all the
layers thereby leading to a recurrently stacked NMT model. We empirically show
that the translation quality of a model that recurrently stacks a single layer
6 times is comparable to the translation quality of a model that stacks 6
separate layers. We also show that using pseudo-parallel corpora by
back-translation leads to further significant improvements in translation
quality.