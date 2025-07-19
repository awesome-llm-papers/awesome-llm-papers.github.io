---
layout: publication
title: 'RAVEN: In-context Learning With Retrieval-augmented Encoder-decoder Language
  Models'
authors: Huang et al.
conference: Transactions of the Association for Computational Linguistics
year: 2023
bibkey: huang2023raven
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.07922'}]
tags: [Merging, Training Techniques, TACL, ACL, Few Shot, In Context Learning, RAG,
  Language Modeling]
---
In this paper, we investigate the in-context learning ability of
retrieval-augmented encoder-decoder language models. We first conduct a
comprehensive analysis of existing models and identify their limitations in
in-context learning, primarily due to a mismatch between pretraining and
inference, as well as a restricted context length. To address these issues, we
propose RAVEN, a model that combines retrieval-augmented masked language
modeling and prefix language modeling. We further introduce Fusion-in-Context
Learning to enhance the few-shot performance by enabling the model to leverage
more in-context examples without requiring additional training. Through
extensive experiments, we demonstrate that our simple yet effective design
significantly improves performance, achieving results comparable to the most
advanced language models in certain scenarios, despite having substantially
fewer parameters. Our work underscores the potential of retrieval-augmented
encoder-decoder language models for in-context learning and encourages further
research in this direction.