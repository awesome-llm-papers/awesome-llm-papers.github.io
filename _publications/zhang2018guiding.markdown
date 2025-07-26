---
layout: publication
title: Guiding Neural Machine Translation With Retrieved Translation Pieces
authors: Jingyi Zhang, Masao Utiyama, Eiichro Sumita, Graham Neubig, Satoshi Nakamura
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: zhang2018guiding
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.02559'}]
tags: ["NAACL", "Retrieval Systems"]
short_authors: Zhang et al.
---
One of the difficulties of neural machine translation (NMT) is the recall and
appropriate translation of low-frequency words or phrases. In this paper, we
propose a simple, fast, and effective method for recalling previously seen
translation examples and incorporating them into the NMT decoding process.
Specifically, for an input sentence, we use a search engine to retrieve
sentence pairs whose source sides are similar with the input sentence, and then
collect \\(n\\)-grams that are both in the retrieved target sentences and aligned
with words that match in the source sentences, which we call "translation
pieces". We compute pseudo-probabilities for each retrieved sentence based on
similarities between the input sentence and the retrieved source sentences, and
use these to weight the retrieved translation pieces. Finally, an existing NMT
model is used to translate the input sentence, with an additional bonus given
to outputs that contain the collected translation pieces. We show our method
improves NMT translation results up to 6 BLEU points on three narrow domain
translation tasks where repetitiveness of the target sentences is particularly
salient. It also causes little increase in the translation time, and compares
favorably to another alternative retrieval-based method with respect to
accuracy, speed, and simplicity of implementation.