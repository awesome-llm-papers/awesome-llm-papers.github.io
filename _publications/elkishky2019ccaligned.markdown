---
layout: publication
title: 'Ccaligned: A Massive Collection Of Cross-lingual Web-document Pairs'
authors: El-kishky et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2019
bibkey: elkishky2019ccaligned
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.06154'}]
tags: [RAG, Reinforcement Learning, EMNLP, Datasets]
---
Cross-lingual document alignment aims to identify pairs of documents in two
distinct languages that are of comparable content or translations of each
other. In this paper, we exploit the signals embedded in URLs to label web
documents at scale with an average precision of 94.5% across different language
pairs. We mine sixty-eight snapshots of the Common Crawl corpus and identify
web document pairs that are translations of each other. We release a new web
dataset consisting of over 392 million URL pairs from Common Crawl covering
documents in 8144 language pairs of which 137 pairs include English. In
addition to curating this massive dataset, we introduce baseline methods that
leverage cross-lingual representations to identify aligned documents based on
their textual content. Finally, we demonstrate the value of this parallel
documents dataset through a downstream task of mining parallel sentences and
measuring the quality of machine translations from models trained on this mined
data. Our objective in releasing this dataset is to foster new research in
cross-lingual NLP across a variety of low, medium, and high-resource languages.