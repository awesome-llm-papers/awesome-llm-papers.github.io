---
layout: publication
title: 'Contextual Embeddings: When Are They Worth It?'
authors: "Simran Arora, Avner May, Jian Zhang, Christopher R\xE9"
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: arora2020contextual
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.09117'}]
tags: ["Evaluation"]
short_authors: Arora et al.
---
We study the settings for which deep contextual embeddings (e.g., BERT) give
large improvements in performance relative to classic pretrained embeddings
(e.g., GloVe), and an even simpler baseline---random word embeddings---focusing
on the impact of the training set size and the linguistic properties of the
task. Surprisingly, we find that both of these simpler baselines can match
contextual embeddings on industry-scale data, and often perform within 5 to 10%
accuracy (absolute) on benchmark tasks. Furthermore, we identify properties of
data for which contextual embeddings give particularly large gains: language
containing complex structure, ambiguous word usage, and words unseen in
training.