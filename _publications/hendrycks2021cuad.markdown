---
layout: publication
title: 'CUAD: An Expert-annotated NLP Dataset For Legal Contract Review'
authors: Dan Hendrycks, Collin Burns, Anya Chen, Spencer Ball
conference: Arxiv
year: 2021
bibkey: hendrycks2021cuad
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.06268'}]
tags: ["Datasets", "Evaluation"]
short_authors: Hendrycks et al.
---
Many specialized domains remain untouched by deep learning, as large labeled
datasets require expensive expert annotators. We address this bottleneck within
the legal domain by introducing the Contract Understanding Atticus Dataset
(CUAD), a new dataset for legal contract review. CUAD was created with dozens
of legal experts from The Atticus Project and consists of over 13,000
annotations. The task is to highlight salient portions of a contract that are
important for a human to review. We find that Transformer models have nascent
performance, but that this performance is strongly influenced by model design
and training dataset size. Despite these promising results, there is still
substantial room for improvement. As one of the only large, specialized NLP
benchmarks annotated by experts, CUAD can serve as a challenging research
benchmark for the broader NLP community.