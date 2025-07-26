---
layout: publication
title: 'Ccmatrix: Mining Billions Of High-quality Parallel Sentences On The WEB'
authors: Holger Schwenk, Guillaume Wenzek, Sergey Edunov, Edouard Grave, Armand Joulin
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: schwenk2019ccmatrix
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.04944'}]
tags: ["Datasets"]
short_authors: Schwenk et al.
---
We show that margin-based bitext mining in a multilingual sentence space can
be applied to monolingual corpora of billions of sentences. We are using ten
snapshots of a curated common crawl corpus (Wenzek et al., 2019) totalling 32.7
billion unique sentences. Using one unified approach for 38 languages, we were
able to mine 4.5 billions parallel sentences, out of which 661 million are
aligned with English. 20 language pairs have more then 30 million parallel
sentences, 112 more then 10 million, and most more than one million, including
direct alignments between many European or Asian languages.
  To evaluate the quality of the mined bitexts, we train NMT systems for most
of the language pairs and evaluate them on TED, WMT and WAT test sets. Using
our mined bitexts only and no human translated parallel data, we achieve a new
state-of-the-art for a single system on the WMT'19 test set for translation
between English and German, Russian and Chinese, as well as German/French. In
particular, our English/German system outperforms the best single one by close
to 4 BLEU points and is almost on pair with best WMT'19 evaluation system which
uses system combination and back-translation. We also achieve excellent results
for distant languages pairs like Russian/Japanese, outperforming the best
submission at the 2019 workshop on Asian Translation (WAT).