---
layout: publication
title: An Empirical Study On Robustness To Spurious Correlations Using Pre-trained
  Language Models
authors: Lifu Tu, Garima Lalwani, Spandana Gella, He He
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: tu2020empirical
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.06778'}]
tags: ["TACL"]
short_authors: Tu et al.
---
Recent work has shown that pre-trained language models such as BERT improve
robustness to spurious correlations in the dataset. Intrigued by these results,
we find that the key to their success is generalization from a small amount of
counterexamples where the spurious correlations do not hold. When such minority
examples are scarce, pre-trained models perform as poorly as models trained
from scratch. In the case of extreme minority, we propose to use multi-task
learning (MTL) to improve generalization. Our experiments on natural language
inference and paraphrase identification show that MTL with the right auxiliary
tasks significantly improves performance on challenging examples without
hurting the in-distribution performance. Further, we show that the gain from
MTL mainly comes from improved generalization from the minority examples. Our
results highlight the importance of data diversity for overcoming spurious
correlations.