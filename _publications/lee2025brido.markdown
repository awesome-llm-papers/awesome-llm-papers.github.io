---
layout: publication
title: 'BRIDO: Bringing Democratic Order To Abstractive Summarization'
authors: Lee Junhyun, Goka Harshith, Ko Hyeonmok
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: lee2025brido
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.18342'}]
tags: [Datasets, Ethics And Bias, Bias Mitigation, ACL]
---
Hallucination refers to the inaccurate, irrelevant, and inconsistent text
generated from large language models (LLMs). While the LLMs have shown great
promise in a variety of tasks, the issue of hallucination still remains a major
challenge for many practical uses. In this paper, we tackle the issue of
hallucination in abstract text summarization by mitigating exposure bias.
Existing models targeted for exposure bias mitigation, namely BRIO, aim for
better summarization quality in the ROUGE score. We propose a model that uses a
similar exposure bias mitigation strategy but with a goal that is aligned with
less hallucination. We conjecture that among a group of candidate outputs, ones
with hallucinations will comprise the minority of the whole group. That is,
candidates with less similarity with others will have a higher chance of
containing hallucinated content. Our method uses this aspect and utilizes
contrastive learning, incentivizing candidates with high inter-candidate ROUGE
scores. We performed experiments on the XSum and CNN/DM summarization datasets,
and our method showed 6.25% and 3.82% improvement, respectively, on the
consistency G-Eval score over BRIO.