---
layout: publication
title: End-to-end Neural Transformer Based Spoken Language Understanding
authors: Radfar Martin, Mouchtaris Athanasios, Kunzmann Siegfried
conference: Interspeech 2020
year: 2020
bibkey: radfar2020end
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.10984'}]
tags: [RAG, Attention Mechanism, INTERSPEECH, Transformer, Model Architecture, Datasets]
---
Spoken language understanding (SLU) refers to the process of inferring the
semantic information from audio signals. While the neural transformers
consistently deliver the best performance among the state-of-the-art neural
architectures in field of natural language processing (NLP), their merits in a
closely related field, i.e., spoken language understanding (SLU) have not beed
investigated. In this paper, we introduce an end-to-end neural
transformer-based SLU model that can predict the variable-length domain,
intent, and slots vectors embedded in an audio signal with no intermediate
token prediction architecture. This new architecture leverages the
self-attention mechanism by which the audio signal is transformed to various
sub-subspaces allowing to extract the semantic context implied by an utterance.
Our end-to-end transformer SLU predicts the domains, intents and slots in the
Fluent Speech Commands dataset with accuracy equal to 98.1 %, 99.6 %, and
99.6 %, respectively and outperforms the SLU models that leverage a
combination of recurrent and convolutional neural networks by 1.4 % while the
size of our model is 25% smaller than that of these architectures.
Additionally, due to independent sub-space projections in the self-attention
layer, the model is highly parallelizable which makes it a good candidate for
on-device SLU.