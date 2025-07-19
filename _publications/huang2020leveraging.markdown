---
layout: publication
title: Leveraging Unpaired Text Data For Training End-to-end Speech-to-intent Systems
authors: Huang et al.
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: huang2020leveraging
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.04284'}]
tags: [RAG, Training Techniques, BERT, ICASSP, Model Architecture, Fine Tuning]
---
Training an end-to-end (E2E) neural network speech-to-intent (S2I) system
that directly extracts intents from speech requires large amounts of
intent-labeled speech data, which is time consuming and expensive to collect.
Initializing the S2I model with an ASR model trained on copious speech data can
alleviate data sparsity. In this paper, we attempt to leverage NLU text
resources. We implemented a CTC-based S2I system that matches the performance
of a state-of-the-art, traditional cascaded SLU system. We performed controlled
experiments with varying amounts of speech and text training data. When only a
tenth of the original data is available, intent classification accuracy
degrades by 7.6% absolute. Assuming we have additional text-to-intent data
(without speech) available, we investigated two techniques to improve the S2I
system: (1) transfer learning, in which acoustic embeddings for intent
classification are tied to fine-tuned BERT text embeddings; and (2) data
augmentation, in which the text-to-intent data is converted into
speech-to-intent data using a multi-speaker text-to-speech system. The proposed
approaches recover 80% of performance lost due to using limited intent-labeled
speech.