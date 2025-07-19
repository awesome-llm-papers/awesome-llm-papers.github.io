---
layout: publication
title: 'Longcoder: A Long-range Pre-trained Language Model For Code Completion'
authors: Guo et al.
conference: Proceedings of the 35th IEEE/ACM International Conference on Automated
  Software Engineering
year: 2023
bibkey: guo2023longcoder
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.14893'}]
tags: [Model Architecture, Efficiency And Optimization, BERT, Evaluation, LLM For
    Code, LLM for Code, Transformer, Datasets, Attention Mechanism]
---
In this paper, we introduce a new task for code completion that focuses on
handling long code input and propose a sparse Transformer model, called
LongCoder, to address this task. LongCoder employs a sliding window mechanism
for self-attention and introduces two types of globally accessible tokens -
bridge tokens and memory tokens - to improve performance and efficiency. Bridge
tokens are inserted throughout the input sequence to aggregate local
information and facilitate global interaction, while memory tokens are included
to highlight important statements that may be invoked later and need to be
memorized, such as package imports and definitions of classes, functions, or
structures. We conduct experiments on a newly constructed dataset that contains
longer code context and the publicly available CodeXGLUE benchmark.
Experimental results demonstrate that LongCoder achieves superior performance
on code completion tasks compared to previous models while maintaining
comparable efficiency in terms of computational resources during inference. All
the codes and data are available at https://github.com/microsoft/CodeBERT.