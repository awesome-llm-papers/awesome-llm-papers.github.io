---
layout: publication
title: 'Convert: Efficient And Accurate Conversational Representations From Transformers'
authors: "Matthew Henderson, I\xF1igo Casanueva, Nikola Mrk\u0161i\u0107, Pei-hao\
  \ Su, Tsung-hsien Wen, Ivan Vuli\u0107"
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: henderson2019convert
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03688'}]
tags: ["Applications", "EMNLP", "Model Architecture", "Tools"]
short_authors: Henderson et al.
---
General-purpose pretrained sentence encoders such as BERT are not ideal for
real-world conversational AI applications; they are computationally heavy,
slow, and expensive to train. We propose ConveRT (Conversational
Representations from Transformers), a pretraining framework for conversational
tasks satisfying all the following requirements: it is effective, affordable,
and quick to train. We pretrain using a retrieval-based response selection
task, effectively leveraging quantization and subword-level parameterization in
the dual encoder to build a lightweight memory- and energy-efficient model. We
show that ConveRT achieves state-of-the-art performance across widely
established response selection tasks. We also demonstrate that the use of
extended dialog history as context yields further performance gains. Finally,
we show that pretrained representations from the proposed encoder can be
transferred to the intent classification task, yielding strong results across
three diverse data sets. ConveRT trains substantially faster than standard
sentence encoders or previous state-of-the-art dual encoders. With its reduced
size and superior performance, we believe this model promises wider portability
and scalability for Conversational AI applications.