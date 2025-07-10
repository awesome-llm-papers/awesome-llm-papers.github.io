---
layout: publication
title: In-context Learning Creates Task Vectors
authors: Roee Hendel, Mor Geva, Amir Globerson
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
citations: 16
bibkey: hendel2023learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.15916'}]
tags: [Model Architecture, Transformer, Tools, Reinforcement Learning, In-Context
    Learning, Training Techniques]
---
In-context learning (ICL) in Large Language Models (LLMs) has emerged as a
powerful new learning paradigm. However, its underlying mechanism is still not
well understood. In particular, it is challenging to map it to the "standard"
machine learning framework, where one uses a training set \\(S\\) to find a
best-fitting function \\(f(x)\\) in some hypothesis class. Here we make progress on
this problem by showing that the functions learned by ICL often have a very
simple structure: they correspond to the transformer LLM whose only inputs are
the query \\(x\\) and a single "task vector" calculated from the training set.
Thus, ICL can be seen as compressing \\(S\\) into a single task vector
\\(\boldsymbol\{\theta\}(S)\\) and then using this task vector to modulate the
transformer to produce the output. We support the above claim via comprehensive
experiments across a range of models and tasks.