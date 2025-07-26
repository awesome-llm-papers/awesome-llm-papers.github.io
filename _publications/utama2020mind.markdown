---
layout: publication
title: 'Mind The Trade-off: Debiasing NLU Models Without Degrading The In-distribution
  Performance'
authors: Prasetya Ajie Utama, Nafise Sadat Moosavi, Iryna Gurevych
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: utama2020mind
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00315'}]
tags: ["Training Techniques"]
short_authors: Prasetya Ajie Utama, Nafise Sadat Moosavi, Iryna Gurevych
---
Models for natural language understanding (NLU) tasks often rely on the
idiosyncratic biases of the dataset, which make them brittle against test cases
outside the training distribution. Recently, several proposed debiasing methods
are shown to be very effective in improving out-of-distribution performance.
However, their improvements come at the expense of performance drop when models
are evaluated on the in-distribution data, which contain examples with higher
diversity. This seemingly inevitable trade-off may not tell us much about the
changes in the reasoning and understanding capabilities of the resulting models
on broader types of examples beyond the small subset represented in the
out-of-distribution data. In this paper, we address this trade-off by
introducing a novel debiasing method, called confidence regularization, which
discourage models from exploiting biases while enabling them to receive enough
incentive to learn from all the training examples. We evaluate our method on
three NLU tasks and show that, in contrast to its predecessors, it improves the
performance on out-of-distribution datasets (e.g., 7pp gain on HANS dataset)
while maintaining the original in-distribution accuracy.