---
layout: publication
title: 'Attention Flows: Analyzing And Comparing Attention Mechanisms In Language
  Models'
authors: Joseph F Derose, Jiayao Wang, Matthew Berger
conference: IEEE Transactions on Visualization and Computer Graphics
year: 2020
bibkey: derose2020attention
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.07053'}]
tags: ["Model Architecture"]
short_authors: Joseph F Derose, Jiayao Wang, Matthew Berger
---
Advances in language modeling have led to the development of deep
attention-based models that are performant across a wide variety of natural
language processing (NLP) problems. These language models are typified by a
pre-training process on large unlabeled text corpora and subsequently
fine-tuned for specific tasks. Although considerable work has been devoted to
understanding the attention mechanisms of pre-trained models, it is less
understood how a model's attention mechanisms change when trained for a target
NLP task. In this paper, we propose a visual analytics approach to
understanding fine-tuning in attention-based language models. Our
visualization, Attention Flows, is designed to support users in querying,
tracing, and comparing attention within layers, across layers, and amongst
attention heads in Transformer-based language models. To help users gain
insight on how a classification decision is made, our design is centered on
depicting classification-based attention at the deepest layer and how attention
from prior layers flows throughout words in the input. Attention Flows supports
the analysis of a single model, as well as the visual comparison between
pre-trained and fine-tuned models via their similarities and differences. We
use Attention Flows to study attention mechanisms in various sentence
understanding tasks and highlight how attention evolves to address the nuances
of solving these tasks.