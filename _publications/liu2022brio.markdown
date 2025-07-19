---
layout: publication
title: 'BRIO: Bringing Order To Abstractive Summarization'
authors: Liu et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: liu2022brio
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.16804'}]
tags: [Datasets, ACL, Training Techniques]
---
Abstractive summarization models are commonly trained using maximum
likelihood estimation, which assumes a deterministic (one-point) target
distribution in which an ideal model will assign all the probability mass to
the reference summary. This assumption may lead to performance degradation
during inference, where the model needs to compare several system-generated
(candidate) summaries that have deviated from the reference summary. To address
this problem, we propose a novel training paradigm which assumes a
non-deterministic distribution so that different candidate summaries are
assigned probability mass according to their quality. Our method achieves a new
state-of-the-art result on the CNN/DailyMail (47.78 ROUGE-1) and XSum (49.07
ROUGE-1) datasets. Further analysis also shows that our model can estimate
probabilities of candidate summaries that are more correlated with their level
of quality.