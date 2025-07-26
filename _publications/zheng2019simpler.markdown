---
layout: publication
title: Simpler And Faster Learning Of Adaptive Policies For Simultaneous Translation
authors: Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: zheng2019simpler
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.01559'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Zheng et al.
---
Simultaneous translation is widely useful but remains challenging. Previous
work falls into two main categories: (a) fixed-latency policies such as Ma et
al. (2019) and (b) adaptive policies such as Gu et al. (2017). The former are
simple and effective, but have to aggressively predict future content due to
diverging source-target word order; the latter do not anticipate, but suffer
from unstable and inefficient training. To combine the merits of both
approaches, we propose a simple supervised-learning framework to learn an
adaptive policy from oracle READ/WRITE sequences generated from parallel text.
At each step, such an oracle sequence chooses to WRITE the next target word if
the available source sentence context provides enough information to do so,
otherwise READ the next source word. Experiments on German<->English show that
our method, without retraining the underlying NMT model, can learn flexible
policies with better BLEU scores and similar latencies compared to previous
work.