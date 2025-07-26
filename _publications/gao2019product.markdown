---
layout: publication
title: Product-aware Answer Generation In E-commerce Question-answering
authors: Shen Gao, Zhaochun Ren, Yihong Eric Zhao, Dongyan Zhao, Dawei Yin, Rui Yan
conference: Proceedings of the Twelfth ACM International Conference on Web Search
  and Data Mining
year: 2019
bibkey: gao2019product
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.07696'}]
tags: ["Datasets", "Evaluation", "Security"]
short_authors: Gao et al.
---
In e-commerce portals, generating answers for product-related questions has
become a crucial task. In this paper, we propose the task of product-aware
answer generation, which tends to generate an accurate and complete answer from
large-scale unlabeled e-commerce reviews and product attributes. Unlike
existing question-answering problems, answer generation in e-commerce confronts
three main challenges: (1) Reviews are informal and noisy; (2) joint modeling
of reviews and key-value product attributes is challenging; (3) traditional
methods easily generate meaningless answers. To tackle above challenges, we
propose an adversarial learning based model, named PAAG, which is composed of
three components: a question-aware review representation module, a key-value
memory network encoding attributes, and a recurrent neural network as a
sequence generator. Specifically, we employ a convolutional discriminator to
distinguish whether our generated answer matches the facts. To extract the
salience part of reviews, an attention-based review reader is proposed to
capture the most relevant words given the question. Conducted on a large-scale
real-world e-commerce dataset, our extensive experiments verify the
effectiveness of each module in our proposed model. Moreover, our experiments
show that our model achieves the state-of-the-art performance in terms of both
automatic metrics and human evaluations.