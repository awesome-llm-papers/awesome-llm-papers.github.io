---
layout: publication
title: 'BERTIN: Efficient Pre-training Of A Spanish Language Model Using Perplexity
  Sampling'
authors: Javier De La Rosa et al.
conference: Procesamiento del Lenguaje Natural 68 (2022) 13-23
year: 2022
citations: 31
bibkey: delarosa2022efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.06814'}]
tags: [Training Techniques, Transformer, Pre-Training, Reinforcement Learning, BERT,
  Model Architecture]
---
The pre-training of large language models usually requires massive amounts of
resources, both in terms of computation and data. Frequently used web sources
such as Common Crawl might contain enough noise to make this pre-training
sub-optimal. In this work, we experiment with different sampling methods from
the Spanish version of mC4, and present a novel data-centric technique which we
name \\(\textit\{perplexity sampling\}\\) that enables the pre-training of language
models in roughly half the amount of steps and using one fifth of the data. The
resulting models are comparable to the current state-of-the-art, and even
achieve better results for certain tasks. Our work is proof of the versatility
of Transformers, and paves the way for small teams to train their models on a
limited budget. Our models are available at this
\\(\href\{https://huggingface.co/bertin-project\}\{URL\}\\).