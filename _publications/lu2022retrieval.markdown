---
layout: publication
title: 'Reacc: A Retrieval-augmented Code Completion Framework'
authors: Shuai Lu et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
citations: 27
bibkey: lu2022retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.07722'}]
tags: [Language Modeling, Model Architecture, Transformer, RAG, Tools, Training Techniques,
  Evaluation]
---
Code completion, which aims to predict the following code token(s) according
to the code context, can improve the productivity of software development.
Recent work has proved that statistical language modeling with transformers can
greatly improve the performance in the code completion task via learning from
large-scale source code datasets. However, current approaches focus only on
code context within the file or project, i.e. internal context. Our distinction
is utilizing "external" context, inspired by human behaviors of copying from
the related code snippets when writing code. Specifically, we propose a
retrieval-augmented code completion framework, leveraging both lexical copying
and referring to code with similar semantics by retrieval. We adopt a
stage-wise training approach that combines a source code retriever and an
auto-regressive language model for programming language. We evaluate our
approach in the code completion task in Python and Java programming languages,
achieving a state-of-the-art performance on CodeXGLUE benchmark.