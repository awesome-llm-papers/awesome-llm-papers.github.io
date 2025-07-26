---
layout: publication
title: Bag-of-words As Target For Neural Machine Translation
authors: Shuming Ma, Xu Sun, Yizhong Wang, Junyang Lin
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2018
bibkey: ma2018bag
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.04871'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Ma et al.
---
A sentence can be translated into more than one correct sentences. However,
most of the existing neural machine translation models only use one of the
correct translations as the targets, and the other correct sentences are
punished as the incorrect sentences in the training stage. Since most of the
correct translations for one sentence share the similar bag-of-words, it is
possible to distinguish the correct translations from the incorrect ones by the
bag-of-words. In this paper, we propose an approach that uses both the
sentences and the bag-of-words as targets in the training stage, in order to
encourage the model to generate the potentially correct sentences that are not
appeared in the training set. We evaluate our model on a Chinese-English
translation dataset, and experiments show our model outperforms the strong
baselines by the BLEU score of 4.55.