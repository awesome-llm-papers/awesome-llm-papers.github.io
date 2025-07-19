---
layout: publication
title: Attention As An RNN
authors: Feng et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: feng2024attention
citations: 732
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.13956'}]
tags: [RAG, Attention Mechanism, Agentic, Transformer, Model Architecture, Time Series,
  Reinforcement Learning, Applications, AAAI, Datasets]
---
The advent of Transformers marked a significant breakthrough in sequence
modelling, providing a highly performant architecture capable of leveraging GPU
parallelism. However, Transformers are computationally expensive at inference
time, limiting their applications, particularly in low-resource settings (e.g.,
mobile and embedded devices). Addressing this, we (1) begin by showing that
attention can be viewed as a special Recurrent Neural Network (RNN) with the
ability to compute its \textit\{many-to-one\} RNN output efficiently. We then (2)
show that popular attention-based models such as Transformers can be viewed as
RNN variants. However, unlike traditional RNNs (e.g., LSTMs), these models
cannot be updated efficiently with new tokens, an important property in
sequence modelling. Tackling this, we (3) introduce a new efficient method of
computing attention's \textit\{many-to-many\} RNN output based on the parallel
prefix scan algorithm. Building on the new attention formulation, we (4)
introduce \textbf\{Aaren\}, an attention-based module that can not only (i) be
trained in parallel (like Transformers) but also (ii) be updated efficiently
with new tokens, requiring only constant memory for inferences (like
traditional RNNs). Empirically, we show Aarens achieve comparable performance
to Transformers on \\(38\\) datasets spread across four popular sequential problem
settings: reinforcement learning, event forecasting, time series
classification, and time series forecasting tasks while being more time and
memory-efficient.