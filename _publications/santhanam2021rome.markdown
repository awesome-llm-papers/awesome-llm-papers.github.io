---
layout: publication
title: 'Rome Was Built In 1776: A Case Study On Factual Correctness In Knowledge-grounded
  Response Generation'
authors: Sashank Santhanam et al.
conference: Arxiv
year: 2021
citations: 22
bibkey: santhanam2021rome
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.05456'}]
tags: [Transformer, RAG, Model Architecture, Evaluation]
---
Recently neural response generation models have leveraged large pre-trained
transformer models and knowledge snippets to generate relevant and informative
responses. However, this does not guarantee that generated responses are
factually correct. In this paper, we examine factual correctness in
knowledge-grounded neural response generation models. We present a human
annotation setup to identify three different response types: responses that are
factually consistent with respect to the input knowledge, responses that
contain hallucinated knowledge, and non-verifiable chitchat style responses. We
use this setup to annotate responses generated using different stateof-the-art
models, knowledge snippets, and decoding strategies. In addition, to facilitate
the development of a factual consistency detector, we automatically create a
new corpus called Conv-FEVER that is adapted from the Wizard of Wikipedia
dataset and includes factually consistent and inconsistent responses. We
demonstrate the benefit of our Conv-FEVER dataset by showing that the models
trained on this data perform reasonably well to detect factually inconsistent
responses with respect to the provided knowledge through evaluation on our
human annotated data. We will release the Conv-FEVER dataset and the human
annotated responses.