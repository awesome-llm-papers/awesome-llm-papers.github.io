---
layout: publication
title: Edinburgh Neural Machine Translation Systems For WMT 16
authors: Rico Sennrich, Barry Haddow, Alexandra Birch
conference: 'Proceedings of the First Conference on Machine Translation: Volume 2,
  Shared Task Papers'
year: 2016
bibkey: sennrich2016edinburgh
citations: 471
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.02891'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Rico Sennrich, Barry Haddow, Alexandra Birch
---
We participated in the WMT 2016 shared news translation task by building
neural translation systems for four language pairs, each trained in both
directions: English<->Czech, English<->German, English<->Romanian and
English<->Russian. Our systems are based on an attentional encoder-decoder,
using BPE subword segmentation for open-vocabulary translation with a fixed
vocabulary. We experimented with using automatic back-translations of the
monolingual News corpus as additional training data, pervasive dropout, and
target-bidirectional models. All reported methods give substantial
improvements, and we see improvements of 4.3--11.2 BLEU over our baseline
systems. In the human evaluation, our systems were the (tied) best constrained
system for 7 out of 8 translation directions in which we participated.