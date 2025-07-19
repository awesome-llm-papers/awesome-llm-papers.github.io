---
layout: publication
title: 'Beyond Error Propagation In Neural Machine Translation: Characteristics Of
  Language Also Matter'
authors: Wu et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: wu2018beyond
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.00120'}]
tags: [EMNLP, GPT, Alt, Ethics And Bias, Transformer, Model Architecture, Language
    Modeling]
---
Neural machine translation usually adopts autoregressive models and suffers
from exposure bias as well as the consequent error propagation problem. Many
previous works have discussed the relationship between error propagation and
the *accuracy drop* (i.e., the left part of the translated sentence is
often better than its right part in left-to-right decoding models) problem. In
this paper, we conduct a series of analyses to deeply understand this problem
and get several interesting findings. (1) The role of error propagation on
accuracy drop is overstated in the literature, although it indeed contributes
to the accuracy drop problem. (2) Characteristics of a language play a more
important role in causing the accuracy drop: the left part of the translation
result in a right-branching language (e.g., English) is more likely to be more
accurate than its right part, while the right part is more accurate for a
left-branching language (e.g., Japanese). Our discoveries are confirmed on
different model structures including Transformer and RNN, and in other sequence
generation tasks such as text summarization.