---
layout: publication
title: 'Coda: Contrast-enhanced And Diversity-promoting Data Augmentation For Natural
  Language Understanding'
authors: Yanru Qu et al.
conference: Arxiv
year: 2020
citations: 35
bibkey: qu2020contrast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.08670'}]
tags: [Training Techniques, Transformer, RAG, Tools, BERT, Efficiency and Optimization,
  Security, Model Architecture]
---
Data augmentation has been demonstrated as an effective strategy for
improving model generalization and data efficiency. However, due to the
discrete nature of natural language, designing label-preserving transformations
for text data tends to be more challenging. In this paper, we propose a novel
data augmentation framework dubbed CoDA, which synthesizes diverse and
informative augmented examples by integrating multiple transformations
organically. Moreover, a contrastive regularization objective is introduced to
capture the global relationship among all the data samples. A momentum encoder
along with a memory bank is further leveraged to better estimate the
contrastive loss. To verify the effectiveness of the proposed framework, we
apply CoDA to Transformer-based models on a wide range of natural language
understanding tasks. On the GLUE benchmark, CoDA gives rise to an average
improvement of 2.2% while applied to the RoBERTa-large model. More importantly,
it consistently exhibits stronger results relative to several competitive data
augmentation and adversarial training base-lines (including the low-resource
settings). Extensive experiments show that the proposed contrastive objective
can be flexibly combined with various data augmentation approaches to further
boost their performance, highlighting the wide applicability of the CoDA
framework.