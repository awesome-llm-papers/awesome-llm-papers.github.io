---
layout: publication
title: 'Code2vec: Learning Distributed Representations Of Code'
authors: Alon et al.
conference: Proceedings of the ACM on Programming Languages
year: 2018
bibkey: alon2018code2vec
citations: 1104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.09473'}]
tags: [Reinforcement Learning, Training Techniques, Datasets]
---
We present a neural model for representing snippets of code as continuous
distributed vectors ("code embeddings"). The main idea is to represent a code
snippet as a single fixed-length \\(\textit\{code vector\}\\), which can be used to
predict semantic properties of the snippet. This is performed by decomposing
code to a collection of paths in its abstract syntax tree, and learning the
atomic representation of each path \\(\textit\{simultaneously\}\\) with learning how
to aggregate a set of them. We demonstrate the effectiveness of our approach by
using it to predict a method's name from the vector representation of its body.
We evaluate our approach by training a model on a dataset of 14M methods. We
show that code vectors trained on this dataset can predict method names from
files that were completely unobserved during training. Furthermore, we show
that our model learns useful method name vectors that capture semantic
similarities, combinations, and analogies. Comparing previous techniques over
the same data set, our approach obtains a relative improvement of over 75%,
being the first to successfully predict method names based on a large,
cross-project, corpus. Our trained model, visualizations and vector
similarities are available as an interactive online demo at
http://code2vec.org. The code, data, and trained models are available at
https://github.com/tech-srl/code2vec.