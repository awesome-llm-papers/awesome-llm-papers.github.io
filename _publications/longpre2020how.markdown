---
layout: publication
title: How Effective Is Task-agnostic Data Augmentation For Pretrained Transformers?
authors: Shayne Longpre, Yu Wang, Christopher Dubois
conference: Arxiv
year: 2020
citations: 31
bibkey: longpre2020how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.01764'}]
tags: [Training Techniques, Transformer, Model Architecture, BERT]
---
Task-agnostic forms of data augmentation have proven widely effective in
computer vision, even on pretrained models. In NLP similar results are reported
most commonly for low data regimes, non-pretrained models, or situationally for
pretrained models. In this paper we ask how effective these techniques really
are when applied to pretrained transformers. Using two popular varieties of
task-agnostic data augmentation (not tailored to any particular task), Easy
Data Augmentation (Wei and Zou, 2019) and Back-Translation (Sennrichet al.,
2015), we conduct a systematic examination of their effects across 5
classification tasks, 6 datasets, and 3 variants of modern pretrained
transformers, including BERT, XLNet, and RoBERTa. We observe a negative result,
finding that techniques which previously reported strong improvements for
non-pretrained models fail to consistently improve performance for pretrained
transformers, even when training data is limited. We hope this empirical
analysis helps inform practitioners where data augmentation techniques may
confer improvements.