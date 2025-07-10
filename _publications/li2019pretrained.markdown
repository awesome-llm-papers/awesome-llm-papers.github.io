---
layout: publication
title: Pretrained Language Models For Document-level Neural Machine Translation
authors: Liangyou Li, Xin Jiang, Qun Liu
conference: Arxiv
year: 2019
citations: 15
bibkey: li2019pretrained
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03110'}]
tags: [BERT, Training Techniques, Model Architecture, SLT]
---
Previous work on document-level NMT usually focuses on limited contexts
because of degraded performance on larger contexts. In this paper, we
investigate on using large contexts with three main contributions: (1)
Different from previous work which pertrained models on large-scale
sentence-level parallel corpora, we use pretrained language models,
specifically BERT, which are trained on monolingual documents; (2) We propose
context manipulation methods to control the influence of large contexts, which
lead to comparable results on systems using small and large contexts; (3) We
introduce a multi-task training for regularization to avoid models overfitting
our training corpora, which further improves our systems together with a deeper
encoder. Experiments are conducted on the widely used IWSLT data sets with
three language pairs, i.e., Chinese--English, French--English and
Spanish--English. Results show that our systems are significantly better than
three previously reported document-level systems.