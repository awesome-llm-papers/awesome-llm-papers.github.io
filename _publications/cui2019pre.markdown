---
layout: publication
title: Pre-training With Whole Word Masking For Chinese BERT
authors: Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Ziqing Yang
conference: IEEE/ACM Transactions on Audio, Speech, and Language Processing
year: 2021
bibkey: cui2019pre
citations: 488
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.08101'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Cui et al.
---
Bidirectional Encoder Representations from Transformers (BERT) has shown
marvelous improvements across various NLP tasks, and its consecutive variants
have been proposed to further improve the performance of the pre-trained
language models. In this paper, we aim to first introduce the whole word
masking (wwm) strategy for Chinese BERT, along with a series of Chinese
pre-trained language models. Then we also propose a simple but effective model
called MacBERT, which improves upon RoBERTa in several ways. Especially, we
propose a new masking strategy called MLM as correction (Mac). To demonstrate
the effectiveness of these models, we create a series of Chinese pre-trained
language models as our baselines, including BERT, RoBERTa, ELECTRA, RBT, etc.
We carried out extensive experiments on ten Chinese NLP tasks to evaluate the
created Chinese pre-trained language models as well as the proposed MacBERT.
Experimental results show that MacBERT could achieve state-of-the-art
performances on many NLP tasks, and we also ablate details with several
findings that may help future research. We open-source our pre-trained language
models for further facilitating our research community. Resources are
available: https://github.com/ymcui/Chinese-BERT-wwm