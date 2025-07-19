---
layout: publication
title: 'Don''t Take The Easy Way Out: Ensemble Based Methods For Avoiding Known Dataset
  Biases'
authors: Clark Christopher, Yatskar Mark, Zettlemoyer Luke
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: clark2019don
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.03683'}]
tags: [RAG, EMNLP, Evaluation, Ethics And Bias, Security, Datasets]
---
State-of-the-art models often make use of superficial patterns in the data
that do not generalize well to out-of-domain or adversarial settings. For
example, textual entailment models often learn that particular key words imply
entailment, irrespective of context, and visual question answering models learn
to predict prototypical answers, without considering evidence in the image. In
this paper, we show that if we have prior knowledge of such biases, we can
train a model to be more robust to domain shift. Our method has two stages: we
(1) train a naive model that makes predictions exclusively based on dataset
biases, and (2) train a robust model as part of an ensemble with the naive one
in order to encourage it to focus on other patterns in the data that are more
likely to generalize. Experiments on five datasets with out-of-domain test sets
show significantly improved robustness in all settings, including a 12 point
gain on a changing priors visual question answering dataset and a 9 point gain
on an adversarial question answering test set.