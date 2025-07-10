---
layout: publication
title: Encoding Syntactic Knowledge In Transformer Encoder For Intent Detection And
  Slot Filling
authors: Jixuan Wang, Kai Wei, Martin Radfar, Weiwei Zhang, Clement Chung
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
citations: 18
bibkey: wang2020encoding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.11689'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Pre-Training, Training
    Techniques, Evaluation]
---
We propose a novel Transformer encoder-based architecture with syntactical
knowledge encoded for intent detection and slot filling. Specifically, we
encode syntactic knowledge into the Transformer encoder by jointly training it
to predict syntactic parse ancestors and part-of-speech of each token via
multi-task learning. Our model is based on self-attention and feed-forward
layers and does not require external syntactic information to be available at
inference time. Experiments show that on two benchmark datasets, our models
with only two Transformer encoder layers achieve state-of-the-art results.
Compared to the previously best performed model without pre-training, our
models achieve absolute F1 score and accuracy improvement of 1.59% and 0.85%
for slot filling and intent detection on the SNIPS dataset, respectively. Our
models also achieve absolute F1 score and accuracy improvement of 0.1% and
0.34% for slot filling and intent detection on the ATIS dataset, respectively,
over the previously best performed model. Furthermore, the visualization of the
self-attention weights illustrates the benefits of incorporating syntactic
information during training.