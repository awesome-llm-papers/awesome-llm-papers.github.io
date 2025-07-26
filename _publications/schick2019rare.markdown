---
layout: publication
title: 'Rare Words: A Major Problem For Contextualized Embeddings And How To Fix It
  By Attentive Mimicking'
authors: "Timo Schick, Hinrich Sch\xFCtze"
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: schick2019rare
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.06707'}]
tags: ["AAAI", "Fine-Tuning", "Training Techniques"]
short_authors: "Timo Schick, Hinrich Sch\xFCtze"
---
Pretraining deep neural network architectures with a language modeling
objective has brought large improvements for many natural language processing
tasks. Exemplified by BERT, a recently proposed such architecture, we
demonstrate that despite being trained on huge amounts of data, deep language
models still struggle to understand rare words. To fix this problem, we adapt
Attentive Mimicking, a method that was designed to explicitly learn embeddings
for rare words, to deep language models. In order to make this possible, we
introduce one-token approximation, a procedure that enables us to use Attentive
Mimicking even when the underlying language model uses subword-based
tokenization, i.e., it does not assign embeddings to all words. To evaluate our
method, we create a novel dataset that tests the ability of language models to
capture semantic properties of words without any task-specific fine-tuning.
Using this dataset, we show that adding our adapted version of Attentive
Mimicking to BERT does indeed substantially improve its understanding of rare
words.