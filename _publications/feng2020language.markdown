---
layout: publication
title: Language-agnostic BERT Sentence Embedding
authors: Fangxiaoyu Feng, Yinfei Yang, Daniel Cer, Naveen Arivazhagan, Wei Wang
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: feng2020language
citations: 309
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.01852'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Feng et al.
---
While BERT is an effective method for learning monolingual sentence
embeddings for semantic similarity and embedding based transfer learning
(Reimers and Gurevych, 2019), BERT based cross-lingual sentence embeddings have
yet to be explored. We systematically investigate methods for learning
multilingual sentence embeddings by combining the best methods for learning
monolingual and cross-lingual representations including: masked language
modeling (MLM), translation language modeling (TLM) (Conneau and Lample, 2019),
dual encoder translation ranking (Guo et al., 2018), and additive margin
softmax (Yang et al., 2019a). We show that introducing a pre-trained
multilingual language model dramatically reduces the amount of parallel
training data required to achieve good performance by 80%. Composing the best
of these methods produces a model that achieves 83.7% bi-text retrieval
accuracy over 112 languages on Tatoeba, well above the 65.5% achieved by
Artetxe and Schwenk (2019b), while still performing competitively on
monolingual transfer learning benchmarks (Conneau and Kiela, 2018). Parallel
data mined from CommonCrawl using our best model is shown to train competitive
NMT models for en-zh and en-de. We publicly release our best multilingual
sentence embedding model for 109+ languages at https://tfhub.dev/google/LaBSE.