---
layout: publication
title: 'ERNIE: Enhanced Language Representation With Informative Entities'
authors: Zhengyan Zhang, Xu Han, Zhiyuan Liu, Xin Jiang, Maosong Sun, Qun Liu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: zhang2019ernie
citations: 1308
additional_links: [{name: Code, url: 'https://github.com/thunlp/ERNIE'}, {name: Paper,
    url: 'https://arxiv.org/abs/1905.07129'}]
tags: ["Model Architecture"]
short_authors: Zhang et al.
---
Neural language representation models such as BERT pre-trained on large-scale
corpora can well capture rich semantic patterns from plain text, and be
fine-tuned to consistently improve the performance of various NLP tasks.
However, the existing pre-trained language models rarely consider incorporating
knowledge graphs (KGs), which can provide rich structured knowledge facts for
better language understanding. We argue that informative entities in KGs can
enhance language representation with external knowledge. In this paper, we
utilize both large-scale textual corpora and KGs to train an enhanced language
representation model (ERNIE), which can take full advantage of lexical,
syntactic, and knowledge information simultaneously. The experimental results
have demonstrated that ERNIE achieves significant improvements on various
knowledge-driven tasks, and meanwhile is comparable with the state-of-the-art
model BERT on other common NLP tasks. The source code of this paper can be
obtained from https://github.com/thunlp/ERNIE.