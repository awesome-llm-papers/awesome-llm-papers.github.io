---
layout: publication
title: 'Simultaneous Translation Policies: From Fixed To Adaptive'
authors: Zheng et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zheng2020simultaneous
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.13169'}]
tags: [ACL, Training Techniques]
---
Adaptive policies are better than fixed policies for simultaneous
translation, since they can flexibly balance the tradeoff between translation
quality and latency based on the current context information. But previous
methods on obtaining adaptive policies either rely on complicated training
process, or underperform simple fixed policies. We design an algorithm to
achieve adaptive policies via a simple heuristic composition of a set of fixed
policies. Experiments on Chinese -> English and German -> English show that our
adaptive policies can outperform fixed ones by up to 4 BLEU points for the same
latency, and more surprisingly, it even surpasses the BLEU score of
full-sentence translation in the greedy mode (and very close to beam mode), but
with much lower latency.