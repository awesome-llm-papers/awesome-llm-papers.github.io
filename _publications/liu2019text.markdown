---
layout: publication
title: Text Summarization With Pretrained Encoders
authors: Yang Liu, Mirella Lapata
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: liu2019text
citations: 1471
additional_links: [{name: Code, url: 'https://github.com/nlpyang/PreSumm'}, {name: Paper,
    url: 'https://arxiv.org/abs/1908.08345'}]
tags: ["Datasets", "Fine-Tuning", "Has Code", "Model Architecture", "Tools"]
short_authors: Yang Liu, Mirella Lapata
---
Bidirectional Encoder Representations from Transformers (BERT) represents the
latest incarnation of pretrained language models which have recently advanced a
wide range of natural language processing tasks. In this paper, we showcase how
BERT can be usefully applied in text summarization and propose a general
framework for both extractive and abstractive models. We introduce a novel
document-level encoder based on BERT which is able to express the semantics of
a document and obtain representations for its sentences. Our extractive model
is built on top of this encoder by stacking several inter-sentence Transformer
layers. For abstractive summarization, we propose a new fine-tuning schedule
which adopts different optimizers for the encoder and the decoder as a means of
alleviating the mismatch between the two (the former is pretrained while the
latter is not). We also demonstrate that a two-staged fine-tuning approach can
further boost the quality of the generated summaries. Experiments on three
datasets show that our model achieves state-of-the-art results across the board
in both extractive and abstractive settings. Our code is available at
https://github.com/nlpyang/PreSumm