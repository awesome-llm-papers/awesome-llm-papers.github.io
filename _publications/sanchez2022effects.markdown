---
layout: publication
title: The Effects Of In-domain Corpus Size On Pre-training BERT
authors: Sanchez Chris, Zhang Zheyuan
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: sanchez2022effects
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.07914'}]
tags: [RAG, Training Techniques, CVPR, Transformer, BERT, Model Architecture, Language
    Modeling, Fine Tuning, Datasets]
---
Many prior language modeling efforts have shown that pre-training on an
in-domain corpus can significantly improve performance on downstream
domain-specific NLP tasks. However, the difficulties associated with collecting
enough in-domain data might discourage researchers from approaching this
pre-training task. In this paper, we conducted a series of experiments by
pre-training Bidirectional Encoder Representations from Transformers (BERT)
with different sizes of biomedical corpora. The results demonstrate that
pre-training on a relatively small amount of in-domain data (4GB) with limited
training steps, can lead to better performance on downstream domain-specific
NLP tasks compared with fine-tuning models pre-trained on general corpora.