---
layout: publication
title: 'Fnet: Mixing Tokens With Fourier Transforms'
authors: James Lee-thorp, Joshua Ainslie, Ilya Eckstein, Santiago Ontanon
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: leethorp2021fnet
citations: 363
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.03824'}]
tags: ["Model Architecture", "NAACL"]
short_authors: Lee-thorp et al.
---
We show that Transformer encoder architectures can be sped up, with limited
accuracy costs, by replacing the self-attention sublayers with simple linear
transformations that "mix" input tokens. These linear mixers, along with
standard nonlinearities in feed-forward layers, prove competent at modeling
semantic relationships in several text classification tasks. Most surprisingly,
we find that replacing the self-attention sublayer in a Transformer encoder
with a standard, unparameterized Fourier Transform achieves 92-97% of the
accuracy of BERT counterparts on the GLUE benchmark, but trains 80% faster on
GPUs and 70% faster on TPUs at standard 512 input lengths. At longer input
lengths, our FNet model is significantly faster: when compared to the
"efficient" Transformers on the Long Range Arena benchmark, FNet matches the
accuracy of the most accurate models, while outpacing the fastest models across
all sequence lengths on GPUs (and across relatively shorter lengths on TPUs).
Finally, FNet has a light memory footprint and is particularly efficient at
smaller model sizes; for a fixed speed and accuracy budget, small FNet models
outperform Transformer counterparts.