---
layout: publication
title: Distilling Task-specific Knowledge From BERT Into Simple Neural Networks
authors: Raphael Tang, Yao Lu, Linqing Liu, Lili Mou, Olga Vechtomova, Jimmy Lin
conference: Arxiv
year: 2019
bibkey: tang2019distilling
citations: 358
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.12136'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Tang et al.
---
In the natural language processing literature, neural networks are becoming
increasingly deeper and complex. The recent poster child of this trend is the
deep language representation model, which includes BERT, ELMo, and GPT. These
developments have led to the conviction that previous-generation, shallower
neural networks for language understanding are obsolete. In this paper,
however, we demonstrate that rudimentary, lightweight neural networks can still
be made competitive without architecture changes, external training data, or
additional input features. We propose to distill knowledge from BERT, a
state-of-the-art language representation model, into a single-layer BiLSTM, as
well as its siamese counterpart for sentence-pair tasks. Across multiple
datasets in paraphrasing, natural language inference, and sentiment
classification, we achieve comparable results with ELMo, while using roughly
100 times fewer parameters and 15 times less inference time.