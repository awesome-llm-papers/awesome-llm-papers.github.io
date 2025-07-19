---
layout: publication
title: Vocabulary Learning Via Optimal Transport For Neural Machine Translation
authors: Xu et al.
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2020
bibkey: xu2020vocabulary
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15671'}]
tags: [ACL, Training Techniques, Alt]
---
The choice of token vocabulary affects the performance of machine
translation. This paper aims to figure out what is a good vocabulary and
whether one can find the optimal vocabulary without trial training. To answer
these questions, we first provide an alternative understanding of the role of
vocabulary from the perspective of information theory. Motivated by this, we
formulate the quest of vocabularization -- finding the best token dictionary
with a proper size -- as an optimal transport (OT) problem. We propose VOLT, a
simple and efficient solution without trial training. Empirical results show
that VOLT outperforms widely-used vocabularies in diverse scenarios, including
WMT-14 English-German and TED's 52 translation directions. For example, VOLT
achieves almost 70% vocabulary size reduction and 0.5 BLEU gain on
English-German translation. Also, compared to BPE-search, VOLT reduces the
search time from 384 GPU hours to 30 GPU hours on English-German translation.
Codes are available at https://github.com/Jingjing-NLP/VOLT .