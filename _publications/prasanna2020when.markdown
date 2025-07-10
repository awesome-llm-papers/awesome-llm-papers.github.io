---
layout: publication
title: When BERT Plays The Lottery, All Tickets Are Winning
authors: Sai Prasanna, Anna Rogers, Anna Rumshisky
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 43
bibkey: prasanna2020when
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00561'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Pruning, Reinforcement
    Learning, Efficiency and Optimization, BERT]
---
Large Transformer-based models were shown to be reducible to a smaller number
of self-attention heads and layers. We consider this phenomenon from the
perspective of the lottery ticket hypothesis, using both structured and
magnitude pruning. For fine-tuned BERT, we show that (a) it is possible to find
subnetworks achieving performance that is comparable with that of the full
model, and (b) similarly-sized subnetworks sampled from the rest of the model
perform worse. Strikingly, with structured pruning even the worst possible
subnetworks remain highly trainable, indicating that most pre-trained BERT
weights are potentially useful. We also study the "good" subnetworks to see if
their success can be attributed to superior linguistic knowledge, but find them
unstable, and not explained by meaningful self-attention patterns.