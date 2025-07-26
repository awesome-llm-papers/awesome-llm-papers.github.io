---
layout: publication
title: A Teacher-student Framework For Zero-resource Neural Machine Translation
authors: Yun Chen, Yang Liu, Yong Cheng, Victor O. K. Li
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: chen2017teacher
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.00753'}]
tags: ["Tools"]
short_authors: Chen et al.
---
While end-to-end neural machine translation (NMT) has made remarkable
progress recently, it still suffers from the data scarcity problem for
low-resource language pairs and domains. In this paper, we propose a method for
zero-resource NMT by assuming that parallel sentences have close probabilities
of generating a sentence in a third language. Based on this assumption, our
method is able to train a source-to-target NMT model ("student") without
parallel corpora available, guided by an existing pivot-to-target NMT model
("teacher") on a source-pivot parallel corpus. Experimental results show that
the proposed method significantly improves over a baseline pivot-based model by
+3.0 BLEU points across various language pairs.