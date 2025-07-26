---
layout: publication
title: 'Consert: A Contrastive Framework For Self-supervised Sentence Representation
  Transfer'
authors: Yuanmeng Yan, Rumei Li, Sirui Wang, Fuzheng Zhang, Wei Wu, Weiran Xu
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: yan2021consert
citations: 424
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.11741'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Yan et al.
---
Learning high-quality sentence representations benefits a wide range of
natural language processing tasks. Though BERT-based pre-trained language
models achieve high performance on many downstream tasks, the native derived
sentence representations are proved to be collapsed and thus produce a poor
performance on the semantic textual similarity (STS) tasks. In this paper, we
present ConSERT, a Contrastive Framework for Self-Supervised Sentence
Representation Transfer, that adopts contrastive learning to fine-tune BERT in
an unsupervised and effective way. By making use of unlabeled texts, ConSERT
solves the collapse issue of BERT-derived sentence representations and make
them more applicable for downstream tasks. Experiments on STS datasets
demonstrate that ConSERT achieves an 8% relative improvement over the previous
state-of-the-art, even comparable to the supervised SBERT-NLI. And when further
incorporating NLI supervision, we achieve new state-of-the-art performance on
STS tasks. Moreover, ConSERT obtains comparable results with only 1000 samples
available, showing its robustness in data scarcity scenarios.