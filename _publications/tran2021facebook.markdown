---
layout: publication
title: Facebook AI WMT21 News Translation Task Submission
authors: Tran et al.
conference: 'Proceedings of the Fourth Conference on Machine Translation (Volume 2:
  Shared Task Papers, Day 1)'
year: 2021
bibkey: tran2021facebook
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.03265'}]
tags: [RAG, WMT, Evaluation]
---
We describe Facebook's multilingual model submission to the WMT2021 shared
task on news translation. We participate in 14 language directions: English to
and from Czech, German, Hausa, Icelandic, Japanese, Russian, and Chinese. To
develop systems covering all these directions, we focus on multilingual models.
We utilize data from all available sources --- WMT, large-scale data mining,
and in-domain backtranslation --- to create high quality bilingual and
multilingual baselines. Subsequently, we investigate strategies for scaling
multilingual model size, such that one system has sufficient capacity for high
quality representations of all eight languages. Our final submission is an
ensemble of dense and sparse Mixture-of-Expert multilingual translation models,
followed by finetuning on in-domain news data and noisy channel reranking.
Compared to previous year's winning submissions, our multilingual system
improved the translation quality on all language directions, with an average
improvement of 2.0 BLEU. In the WMT2021 task, our system ranks first in 10
directions based on automatic evaluation.