---
layout: publication
title: Pre-training Transformers As Energy-based Cloze Models
authors: Clark et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: clark2020pre
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.08561'}]
tags: [Training Techniques, EMNLP, Masked Language Model, Transformer, BERT, Model
    Architecture, Reinforcement Learning]
---
We introduce Electric, an energy-based cloze model for representation
learning over text. Like BERT, it is a conditional generative model of tokens
given their contexts. However, Electric does not use masking or output a full
distribution over tokens that could occur in a context. Instead, it assigns a
scalar energy score to each input token indicating how likely it is given its
context. We train Electric using an algorithm based on noise-contrastive
estimation and elucidate how this learning objective is closely related to the
recently proposed ELECTRA pre-training method. Electric performs well when
transferred to downstream tasks and is particularly effective at producing
likelihood scores for text: it re-ranks speech recognition n-best lists better
than language models and much faster than masked language models. Furthermore,
it offers a clearer and more principled view of what ELECTRA learns during
pre-training.