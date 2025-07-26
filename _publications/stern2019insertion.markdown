---
layout: publication
title: 'Insertion Transformer: Flexible Sequence Generation Via Insertion Operations'
authors: Mitchell Stern, William Chan, Jamie Kiros, Jakob Uszkoreit
conference: Arxiv
year: 2019
bibkey: stern2019insertion
citations: 160
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.03249'}]
tags: ["Model Architecture"]
short_authors: Stern et al.
---
We present the Insertion Transformer, an iterative, partially autoregressive
model for sequence generation based on insertion operations. Unlike typical
autoregressive models which rely on a fixed, often left-to-right ordering of
the output, our approach accommodates arbitrary orderings by allowing for
tokens to be inserted anywhere in the sequence during decoding. This
flexibility confers a number of advantages: for instance, not only can our
model be trained to follow specific orderings such as left-to-right generation
or a binary tree traversal, but it can also be trained to maximize entropy over
all valid insertions for robustness. In addition, our model seamlessly
accommodates both fully autoregressive generation (one insertion at a time) and
partially autoregressive generation (simultaneous insertions at multiple
locations). We validate our approach by analyzing its performance on the WMT
2014 English-German machine translation task under various settings for
training and decoding. We find that the Insertion Transformer outperforms many
prior non-autoregressive approaches to translation at comparable or better
levels of parallelism, and successfully recovers the performance of the
original Transformer while requiring only logarithmically many iterations
during decoding.