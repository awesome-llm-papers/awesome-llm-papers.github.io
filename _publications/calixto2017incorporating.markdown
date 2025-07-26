---
layout: publication
title: Incorporating Global Visual Features Into Attention-based Neural Machine Translation
authors: Iacer Calixto, Qun Liu, Nick Campbell
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: calixto2017incorporating
citations: 154
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1701.06521'}]
tags: ["EMNLP"]
short_authors: Iacer Calixto, Qun Liu, Nick Campbell
---
We introduce multi-modal, attention-based neural machine translation (NMT)
models which incorporate visual features into different parts of both the
encoder and the decoder. We utilise global image features extracted using a
pre-trained convolutional neural network and incorporate them (i) as words in
the source sentence, (ii) to initialise the encoder hidden state, and (iii) as
additional data to initialise the decoder hidden state. In our experiments, we
evaluate how these different strategies to incorporate global image features
compare and which ones perform best. We also study the impact that adding
synthetic multi-modal, multilingual data brings and find that the additional
data have a positive impact on multi-modal models. We report new
state-of-the-art results and our best models also significantly improve on a
comparable phrase-based Statistical MT (PBSMT) model trained on the Multi30k
data set according to all metrics evaluated. To the best of our knowledge, it
is the first time a purely neural model significantly improves over a PBSMT
model on all metrics evaluated on this data set.