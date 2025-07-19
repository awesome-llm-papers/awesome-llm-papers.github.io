---
layout: publication
title: Generative Spoken Language Modeling From Raw Audio
authors: Lakhotia et al.
conference: Arxiv
year: 2021
bibkey: lakhotia2021generative
citations: 128
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.01192'}]
tags: [Model Architecture, Language Modeling, Evaluation, BERT]
---
We introduce Generative Spoken Language Modeling, the task of learning the
acoustic and linguistic characteristics of a language from raw audio (no text,
no labels), and a set of metrics to automatically evaluate the learned
representations at acoustic and linguistic levels for both encoding and
generation. We set up baseline systems consisting of a discrete speech encoder
(returning pseudo-text units), a generative language model (trained on
pseudo-text), and a speech decoder (generating a waveform from pseudo-text) all
trained without supervision and validate the proposed metrics with human
evaluation. Across 3 speech encoders (CPC, wav2vec 2.0, HuBERT), we find that
the number of discrete units (50, 100, or 200) matters in a task-dependent and
encoder-dependent way, and that some combinations approach text-based systems.