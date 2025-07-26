---
layout: publication
title: 'Explicit Sparse Transformer: Concentrated Attention Through Explicit Selection'
authors: Guangxiang Zhao, Junyang Lin, Zhiyuan Zhang, Xuancheng Ren, Qi Su, Xu Sun
conference: Arxiv
year: 2019
bibkey: zhao2019explicit
citations: 80
additional_links: [{name: Code, url: 'https://github.com/lancopku/Explicit-Sparse-Transformer'},
  {name: Paper, url: 'https://arxiv.org/abs/1912.11637'}]
tags: ["Model Architecture"]
short_authors: Zhao et al.
---
Self-attention based Transformer has demonstrated the state-of-the-art
performances in a number of natural language processing tasks. Self-attention
is able to model long-term dependencies, but it may suffer from the extraction
of irrelevant information in the context. To tackle the problem, we propose a
novel model called \textbf\{Explicit Sparse Transformer\}. Explicit Sparse
Transformer is able to improve the concentration of attention on the global
context through an explicit selection of the most relevant segments. Extensive
experimental results on a series of natural language processing and computer
vision tasks, including neural machine translation, image captioning, and
language modeling, all demonstrate the advantages of Explicit Sparse
Transformer in model performance. We also show that our proposed sparse
attention method achieves comparable or better results than the previous sparse
attention method, but significantly reduces training and testing time. For
example, the inference speed is twice that of sparsemax in Transformer model.
Code will be available at
https://github.com/lancopku/Explicit-Sparse-Transformer