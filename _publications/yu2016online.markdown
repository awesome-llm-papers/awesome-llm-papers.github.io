---
layout: publication
title: Online Segment To Segment Neural Transduction
authors: Lei Yu, Jan Buys, Phil Blunsom
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: yu2016online
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.08194'}]
tags: ["EMNLP"]
short_authors: Lei Yu, Jan Buys, Phil Blunsom
---
We introduce an online neural sequence to sequence model that learns to
alternate between encoding and decoding segments of the input as it is read. By
independently tracking the encoding and decoding representations our algorithm
permits exact polynomial marginalization of the latent segmentation during
training, and during decoding beam search is employed to find the best
alignment path together with the predicted output sequence. Our model tackles
the bottleneck of vanilla encoder-decoders that have to read and memorize the
entire input sequence in their fixed-length hidden states before producing any
output. It is different from previous attentive models in that, instead of
treating the attention weights as output of a deterministic function, our model
assigns attention weights to a sequential latent variable which can be
marginalized out and permits online generation. Experiments on abstractive
sentence summarization and morphological inflection show significant
performance gains over the baseline encoder-decoders.