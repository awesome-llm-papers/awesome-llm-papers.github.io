---
layout: publication
title: Improving Lexical Choice In Neural Machine Translation
authors: Toan Q. Nguyen, David Chiang
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: nguyen2017improving
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1710.01329'}]
tags: ["NAACL"]
short_authors: Toan Q. Nguyen, David Chiang
---
We explore two solutions to the problem of mistranslating rare words in
neural machine translation. First, we argue that the standard output layer,
which computes the inner product of a vector representing the context with all
possible output word embeddings, rewards frequent words disproportionately, and
we propose to fix the norms of both vectors to a constant value. Second, we
integrate a simple lexical module which is jointly trained with the rest of the
model. We evaluate our approaches on eight language pairs with data sizes
ranging from 100k to 8M words, and achieve improvements of up to +4.3 BLEU,
surpassing phrase-based translation in nearly all settings.