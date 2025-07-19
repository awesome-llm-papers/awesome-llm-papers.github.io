---
layout: publication
title: Facebook Fair's WMT19 News Translation Task Submission
authors: Ng et al.
conference: 'Proceedings of the Fourth Conference on Machine Translation (Volume 2:
  Shared Task Papers, Day 1)'
year: 2019
bibkey: ng2019facebook
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.06616'}]
tags: [Model Architecture, Time Series, Evaluation, Transformer, WMT]
---
This paper describes Facebook FAIR's submission to the WMT19 shared news
translation task. We participate in two language pairs and four language
directions, English <-> German and English <-> Russian. Following our
submission from last year, our baseline systems are large BPE-based transformer
models trained with the Fairseq sequence modeling toolkit which rely on sampled
back-translations. This year we experiment with different bitext data filtering
schemes, as well as with adding filtered back-translated data. We also ensemble
and fine-tune our models on domain-specific data, then decode using noisy
channel model reranking. Our submissions are ranked first in all four
directions of the human evaluation campaign. On En->De, our system
significantly outperforms other systems as well as human translations. This
system improves upon our WMT'18 submission by 4.5 BLEU points.