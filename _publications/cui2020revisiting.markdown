---
layout: publication
title: Revisiting Pre-trained Models For Chinese Natural Language Processing
authors: Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Shijin Wang, Guoping Hu
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: cui2020revisiting
citations: 634
additional_links: [{name: Code, url: 'https://github.com/ymcui/MacBERT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2004.13922'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Cui et al.
---
Bidirectional Encoder Representations from Transformers (BERT) has shown
marvelous improvements across various NLP tasks, and consecutive variants have
been proposed to further improve the performance of the pre-trained language
models. In this paper, we target on revisiting Chinese pre-trained language
models to examine their effectiveness in a non-English language and release the
Chinese pre-trained language model series to the community. We also propose a
simple but effective model called MacBERT, which improves upon RoBERTa in
several ways, especially the masking strategy that adopts MLM as correction
(Mac). We carried out extensive experiments on eight Chinese NLP tasks to
revisit the existing pre-trained language models as well as the proposed
MacBERT. Experimental results show that MacBERT could achieve state-of-the-art
performances on many NLP tasks, and we also ablate details with several
findings that may help future research. Resources available:
https://github.com/ymcui/MacBERT