---
layout: publication
title: 'Dissecting Contextual Word Embeddings: Architecture And Representation'
authors: Matthew E. Peters, Mark Neumann, Luke Zettlemoyer, Wen-tau Yih
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: peters2018dissecting
citations: 446
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.08949'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Peters et al.
---
Contextual word representations derived from pre-trained bidirectional
language models (biLMs) have recently been shown to provide significant
improvements to the state of the art for a wide range of NLP tasks. However,
many questions remain as to how and why these models are so effective. In this
paper, we present a detailed empirical study of how the choice of neural
architecture (e.g. LSTM, CNN, or self attention) influences both end task
accuracy and qualitative properties of the representations that are learned. We
show there is a tradeoff between speed and accuracy, but all architectures
learn high quality contextual representations that outperform word embeddings
for four challenging NLP tasks. Additionally, all architectures learn
representations that vary with network depth, from exclusively morphological
based at the word embedding layer through local syntax based in the lower
contextual layers to longer range semantics such coreference at the upper
layers. Together, these results suggest that unsupervised biLMs, independent of
architecture, are learning much more about the structure of language than
previously appreciated.