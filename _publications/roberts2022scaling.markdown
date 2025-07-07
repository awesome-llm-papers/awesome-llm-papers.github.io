---
layout: publication
title: Scaling Up Models And Data With \(\texttt{t5x}\) And \(\texttt{seqio}\)
authors: Adam Roberts et al.
conference: Arxiv
year: 2022
citations: 47
bibkey: roberts2022scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.17189'}, {name: Code,
    url: 'https://github.com/google-research/t5x'}, {name: Code, url: 'https://github.com/google/seqio,'}]
tags: [GPT, Training Techniques, Tools, Has Code, Model Architecture]
---
Recent neural network-based language models have benefited greatly from
scaling up the size of training datasets and the number of parameters in the
models themselves. Scaling can be complicated due to various factors including
the need to distribute computation on supercomputer clusters (e.g., TPUs),
prevent bottlenecks when infeeding data, and ensure reproducible results. In
this work, we present two software libraries that ease these issues:
\\(\texttt\{t5x\}\\) simplifies the process of building and training large language
models at scale while maintaining ease of use, and \\(\texttt\{seqio\}\\) provides a
task-based API for simple creation of fast and reproducible training data and
evaluation pipelines. These open-source libraries have been used to train
models with hundreds of billions of parameters on datasets with multiple
terabytes of training data.
  Along with the libraries, we release configurations and instructions for
T5-like encoder-decoder models as well as GPT-like decoder-only architectures.
  \\(\texttt\{t5x\}\\) and \\(\texttt\{seqio\}\\) are open source and available at
https://github.com/google-research/t5x and https://github.com/google/seqio,
respectively.