---
layout: publication
title: 'Linkbert: Pretraining Language Models With Document Links'
authors: Michihiro Yasunaga, Jure Leskovec, Percy Liang
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: yasunaga2022linkbert
citations: 200
additional_links: [{name: Code, url: 'https://github.com/michiyasunaga/LinkBERT'},
  {name: Paper, url: 'https://arxiv.org/abs/2203.15827'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Michihiro Yasunaga, Jure Leskovec, Percy Liang
---
Language model (LM) pretraining can learn various knowledge from text
corpora, helping downstream tasks. However, existing methods such as BERT model
a single document, and do not capture dependencies or knowledge that span
across documents. In this work, we propose LinkBERT, an LM pretraining method
that leverages links between documents, e.g., hyperlinks. Given a text corpus,
we view it as a graph of documents and create LM inputs by placing linked
documents in the same context. We then pretrain the LM with two joint
self-supervised objectives: masked language modeling and our new proposal,
document relation prediction. We show that LinkBERT outperforms BERT on various
downstream tasks across two domains: the general domain (pretrained on
Wikipedia with hyperlinks) and biomedical domain (pretrained on PubMed with
citation links). LinkBERT is especially effective for multi-hop reasoning and
few-shot QA (+5% absolute improvement on HotpotQA and TriviaQA), and our
biomedical LinkBERT sets new states of the art on various BioNLP tasks (+7% on
BioASQ and USMLE). We release our pretrained models, LinkBERT and BioLinkBERT,
as well as code and data at https://github.com/michiyasunaga/LinkBERT.