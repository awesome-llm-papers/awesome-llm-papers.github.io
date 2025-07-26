---
layout: publication
title: Using The Output Embedding To Improve Language Models
authors: Ofir Press, Lior Wolf
conference: 'Proceedings of the 15th Conference of the European Chapter of the Association
  for Computational Linguistics: Volume 2, Short Papers'
year: 2017
bibkey: press2016using
citations: 635
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.05859'}]
tags: ["Training Techniques"]
short_authors: Ofir Press, Lior Wolf
---
We study the topmost weight matrix of neural network language models. We show
that this matrix constitutes a valid word embedding. When training language
models, we recommend tying the input embedding and this output embedding. We
analyze the resulting update rules and show that the tied embedding evolves in
a more similar way to the output embedding than to the input embedding in the
untied model. We also offer a new method of regularizing the output embedding.
Our methods lead to a significant reduction in perplexity, as we are able to
show on a variety of neural network language models. Finally, we show that
weight tying can reduce the size of neural translation models to less than half
of their original size without harming their performance.