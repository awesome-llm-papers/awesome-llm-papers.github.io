---
layout: publication
title: Coherent Dialogue With Attention-based Language Models
authors: Hongyuan Mei, Mohit Bansal, Matthew R. Walter
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2017
bibkey: mei2016coherent
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.06997'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Hongyuan Mei, Mohit Bansal, Matthew R. Walter
---
We model coherent conversation continuation via RNN-based dialogue models
equipped with a dynamic attention mechanism. Our attention-RNN language model
dynamically increases the scope of attention on the history as the conversation
continues, as opposed to standard attention (or alignment) models with a fixed
input scope in a sequence-to-sequence model. This allows each generated word to
be associated with the most relevant words in its corresponding conversation
history. We evaluate the model on two popular dialogue datasets, the
open-domain MovieTriples dataset and the closed-domain Ubuntu Troubleshoot
dataset, and achieve significant improvements over the state-of-the-art and
baselines on several metrics, including complementary diversity-based metrics,
human evaluation, and qualitative visualizations. We also show that a vanilla
RNN with dynamic attention outperforms more complex memory models (e.g., LSTM
and GRU) by allowing for flexible, long-distance memory. We promote further
coherence via topic modeling-based reranking.