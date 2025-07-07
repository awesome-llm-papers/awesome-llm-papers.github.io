---
layout: publication
title: Generated Knowledge Prompting For Commonsense Reasoning
authors: Jiacheng Liu et al.
conference: Arxiv
year: 2021
citations: 74
bibkey: liu2021generated
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08387'}, {name: Code,
    url: 'https://github.com/liujch1998/GKP'}]
tags: [Has Code, Prompting]
---
It remains an open question whether incorporating external knowledge benefits
commonsense reasoning while maintaining the flexibility of pretrained sequence
models. To investigate this question, we develop generated knowledge prompting,
which consists of generating knowledge from a language model, then providing
the knowledge as additional input when answering a question. Our method does
not require task-specific supervision for knowledge integration, or access to a
structured knowledge base, yet it improves performance of large-scale,
state-of-the-art models on four commonsense reasoning tasks, achieving
state-of-the-art results on numerical commonsense (NumerSense), general
commonsense (CommonsenseQA 2.0), and scientific commonsense (QASC) benchmarks.
Generated knowledge prompting highlights large-scale language models as
flexible sources of external knowledge for improving commonsense reasoning. Our
code is available at https://github.com/liujch1998/GKP