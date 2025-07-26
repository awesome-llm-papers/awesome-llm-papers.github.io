---
layout: publication
title: Improving The Transformer Translation Model With Document-level Context
authors: Jiacheng Zhang, Huanbo Luan, Maosong Sun, Feifei Zhai, Jingfang Xu, Min Zhang,
  Yang Liu
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: zhang2018improving
citations: 262
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.03581'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Zhang et al.
---
Although the Transformer translation model (Vaswani et al., 2017) has
achieved state-of-the-art performance in a variety of translation tasks, how to
use document-level context to deal with discourse phenomena problematic for
Transformer still remains a challenge. In this work, we extend the Transformer
model with a new context encoder to represent document-level context, which is
then incorporated into the original encoder and decoder. As large-scale
document-level parallel corpora are usually not available, we introduce a
two-step training method to take full advantage of abundant sentence-level
parallel corpora and limited document-level parallel corpora. Experiments on
the NIST Chinese-English datasets and the IWSLT French-English datasets show
that our approach improves over Transformer significantly.