---
layout: publication
title: 'Summareranker: A Multi-task Mixture-of-experts Re-ranking Framework For Abstractive
  Summarization'
authors: Mathieu Ravaut, Shafiq Joty, Nancy F. Chen
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: ravaut2022summareranker
citations: 60
additional_links: [{name: Code, url: 'https://github.com/ntunlp/SummaReranker'}, {
    name: Paper, url: 'https://arxiv.org/abs/2203.06569'}]
tags: ["Tools"]
short_authors: Mathieu Ravaut, Shafiq Joty, Nancy F. Chen
---
Sequence-to-sequence neural networks have recently achieved great success in
abstractive summarization, especially through fine-tuning large pre-trained
language models on the downstream dataset. These models are typically decoded
with beam search to generate a unique summary. However, the search space is
very large, and with the exposure bias, such decoding is not optimal. In this
paper, we show that it is possible to directly train a second-stage model
performing re-ranking on a set of summary candidates. Our mixture-of-experts
SummaReranker learns to select a better candidate and consistently improves the
performance of the base model. With a base PEGASUS, we push ROUGE scores by
5.44% on CNN-DailyMail (47.16 ROUGE-1), 1.31% on XSum (48.12 ROUGE-1) and 9.34%
on Reddit TIFU (29.83 ROUGE-1), reaching a new state-of-the-art. Our code and
checkpoints will be available at https://github.com/ntunlp/SummaReranker.