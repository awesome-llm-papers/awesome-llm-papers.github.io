---
layout: publication
title: GRUEN For Evaluating Linguistic Quality Of Generated Text
authors: Wanzheng Zhu, Suma Bhat
conference: Arxiv
year: 2020
citations: 21
bibkey: zhu2020gruen
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02498'}]
tags: [Model Architecture, BERT]
---
Automatic evaluation metrics are indispensable for evaluating generated text.
To date, these metrics have focused almost exclusively on the content selection
aspect of the system output, ignoring the linguistic quality aspect altogether.
We bridge this gap by proposing GRUEN for evaluating Grammaticality,
non-Redundancy, focUs, structure and coherENce of generated text. GRUEN
utilizes a BERT-based model and a class of syntactic, semantic, and contextual
features to examine the system output. Unlike most existing evaluation metrics
which require human references as an input, GRUEN is reference-less and
requires only the system output. Besides, it has the advantage of being
unsupervised, deterministic, and adaptable to various tasks. Experiments on
seven datasets over four language generation tasks show that the proposed
metric correlates highly with human judgments.