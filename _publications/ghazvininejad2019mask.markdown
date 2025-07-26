---
layout: publication
title: 'Mask-predict: Parallel Decoding Of Conditional Masked Language Models'
authors: Marjan Ghazvininejad, Omer Levy, Yinhan Liu, Luke Zettlemoyer
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: ghazvininejad2019mask
citations: 443
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09324'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Ghazvininejad et al.
---
Most machine translation systems generate text autoregressively from left to
right. We, instead, use a masked language modeling objective to train a model
to predict any subset of the target words, conditioned on both the input text
and a partially masked target translation. This approach allows for efficient
iterative decoding, where we first predict all of the target words
non-autoregressively, and then repeatedly mask out and regenerate the subset of
words that the model is least confident about. By applying this strategy for a
constant number of iterations, our model improves state-of-the-art performance
levels for non-autoregressive and parallel decoding translation models by over
4 BLEU on average. It is also able to reach within about 1 BLEU point of a
typical left-to-right transformer model, while decoding significantly faster.