---
layout: publication
title: Evaluating Commonsense In Pre-trained Language Models
authors: Zhou et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: zhou2019evaluating
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.11931'}]
tags: [Training Techniques, GPT, Evaluation, BERT, Model Architecture, Language Modeling,
  Reinforcement Learning, Security, AAAI, Datasets, Merging]
---
Contextualized representations trained over large raw text data have given
remarkable improvements for NLP tasks including question answering and reading
comprehension. There have been works showing that syntactic, semantic and word
sense knowledge are contained in such representations, which explains why they
benefit such tasks. However, relatively little work has been done investigating
commonsense knowledge contained in contextualized representations, which is
crucial for human question answering and reading comprehension. We study the
commonsense ability of GPT, BERT, XLNet, and RoBERTa by testing them on seven
challenging benchmarks, finding that language modeling and its variants are
effective objectives for promoting models' commonsense ability while
bi-directional context and larger training set are bonuses. We additionally
find that current models do poorly on tasks require more necessary inference
steps. Finally, we test the robustness of models by making dual test cases,
which are correlated so that the correct prediction of one sample should lead
to correct prediction of the other. Interestingly, the models show confusion on
these test cases, which suggests that they learn commonsense at the surface
rather than the deep level. We release a test set, named CATs publicly, for
future research.