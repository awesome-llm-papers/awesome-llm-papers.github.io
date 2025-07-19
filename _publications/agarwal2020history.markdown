---
layout: publication
title: 'History For Visual Dialog: Do We Really Need It?'
authors: Agarwal et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: agarwal2020history
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.07493'}]
tags: [Model Architecture, Evaluation, ACL, RAG, Datasets, Attention Mechanism]
---
Visual Dialog involves "understanding" the dialog history (what has been
discussed previously) and the current question (what is asked), in addition to
grounding information in the image, to generate the correct response. In this
paper, we show that co-attention models which explicitly encode dialog history
outperform models that don't, achieving state-of-the-art performance (72 % NDCG
on val set). However, we also expose shortcomings of the crowd-sourcing dataset
collection procedure by showing that history is indeed only required for a
small amount of the data and that the current evaluation metric encourages
generic replies. To that end, we propose a challenging subset (VisDialConv) of
the VisDial val set and provide a benchmark of 63% NDCG.