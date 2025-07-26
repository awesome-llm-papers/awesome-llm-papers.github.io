---
layout: publication
title: Multilingual Speech Translation With Efficient Finetuning Of Pretrained Models
authors: Xian Li, Changhan Wang, Yun Tang, Chau Tran, Yuqing Tang, Juan Pino, Alexei
  Baevski, Alexis Conneau, Michael Auli
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: li2020multilingual
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12829'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Li et al.
---
We present a simple yet effective approach to build multilingual
speech-to-text (ST) translation by efficient transfer learning from pretrained
speech encoder and text decoder. Our key finding is that a minimalistic LNA
(LayerNorm and Attention) finetuning can achieve zero-shot crosslingual and
cross-modality transfer ability by only finetuning less than 10% of the
pretrained parameters. This enables effectively leveraging large pretrained
models with low training cost. Using wav2vec 2.0 for acoustic modeling, and
mBART for multilingual text generation, our approach advanced the new
state-of-the-art for 34 translation directions (and surpassing cascaded ST for
23 of them) on large-scale multilingual ST benchmark CoVoST 2 (+6.4 BLEU on
average across 15 En-X directions and +5.1 BLEU on average across 19 X-En
directions). Our approach demonstrates strong zero-shot performance in a
many-to-many multilingual model (+5.7 BLEU on average across 18 non-English
directions), making it an appealing approach for attaining high-quality speech
translation with improved parameter and data efficiency.