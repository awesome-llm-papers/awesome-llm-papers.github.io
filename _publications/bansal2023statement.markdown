---
layout: publication
title: Statement-based Memory For Neural Source Code Summarization
authors: Bansal et al.
conference: Proceedings of the ACM/IEEE 42nd International Conference on Software
  Engineering
year: 2023
bibkey: bansal2023statement
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.11709'}]
tags: [Model Architecture, Training Techniques, LLM For Code, LLM for Code, Transformer,
  Datasets]
---
Source code summarization is the task of writing natural language
descriptions of source code behavior. Code summarization underpins software
documentation for programmers. Short descriptions of code help programmers
understand the program quickly without having to read the code itself. Lately,
neural source code summarization has emerged as the frontier of research into
automated code summarization techniques. By far the most popular targets for
summarization are program subroutines. The idea, in a nutshell, is to train an
encoder-decoder neural architecture using large sets of examples of subroutines
extracted from code repositories. The encoder represents the code and the
decoder represents the summary. However, most current approaches attempt to
treat the subroutine as a single unit. For example, by taking the entire
subroutine as input to a Transformer or RNN-based encoder. But code behavior
tends to depend on the flow from statement to statement. Normally dynamic
analysis may shed light on this flow, but dynamic analysis on hundreds of
thousands of examples in large datasets is not practical. In this paper, we
present a statement-based memory encoder that learns the important elements of
flow during training, leading to a statement-based subroutine representation
without the need for dynamic analysis. We implement our encoder for code
summarization and demonstrate a significant improvement over the
state-of-the-art.