---
layout: publication
title: 'Sockeye: A Toolkit For Neural Machine Translation'
authors: Felix Hieber, Tobias Domhan, Michael Denkowski, David Vilar, Artem Sokolov,
  Ann Clifton, Matt Post
conference: Arxiv
year: 2017
bibkey: hieber2017sockeye
citations: 205
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.05690'}]
tags: ["Model Architecture", "Tools", "Training Techniques"]
short_authors: Hieber et al.
---
We describe Sockeye (version 1.12), an open-source sequence-to-sequence
toolkit for Neural Machine Translation (NMT). Sockeye is a production-ready
framework for training and applying models as well as an experimental platform
for researchers. Written in Python and built on MXNet, the toolkit offers
scalable training and inference for the three most prominent encoder-decoder
architectures: attentional recurrent neural networks, self-attentional
transformers, and fully convolutional networks. Sockeye also supports a wide
range of optimizers, normalization and regularization techniques, and inference
improvements from current NMT literature. Users can easily run standard
training recipes, explore different model settings, and incorporate new ideas.
In this paper, we highlight Sockeye's features and benchmark it against other
NMT toolkits on two language arcs from the 2017 Conference on Machine
Translation (WMT): English-German and Latvian-English. We report competitive
BLEU scores across all three architectures, including an overall best score for
Sockeye's transformer implementation. To facilitate further comparison, we
release all system outputs and training scripts used in our experiments. The
Sockeye toolkit is free software released under the Apache 2.0 license.