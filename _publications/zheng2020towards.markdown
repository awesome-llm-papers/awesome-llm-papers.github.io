---
layout: publication
title: Towards Making The Most Of Context In Neural Machine Translation
authors: Zaixiang Zheng, Xiang Yue, Shujian Huang, Jiajun Chen, Alexandra Birch
conference: Proceedings of the Twenty-Ninth International Joint Conference on Artificial
  Intelligence
year: 2020
bibkey: zheng2020towards
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.07982'}]
tags: ["IJCAI", "Model Architecture"]
short_authors: Zheng et al.
---
Document-level machine translation manages to outperform sentence level
models by a small margin, but have failed to be widely adopted. We argue that
previous research did not make a clear use of the global context, and propose a
new document-level NMT framework that deliberately models the local context of
each sentence with the awareness of the global context of the document in both
source and target languages. We specifically design the model to be able to
deal with documents containing any number of sentences, including single
sentences. This unified approach allows our model to be trained elegantly on
standard datasets without needing to train on sentence and document level data
separately. Experimental results demonstrate that our model outperforms
Transformer baselines and previous document-level NMT models with substantial
margins of up to 2.1 BLEU on state-of-the-art baselines. We also provide
analyses which show the benefit of context far beyond the neighboring two or
three sentences, which previous studies have typically incorporated.