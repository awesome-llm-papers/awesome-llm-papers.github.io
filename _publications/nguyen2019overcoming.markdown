---
layout: publication
title: Overcoming Data Limitation In Medical Visual Question Answering
authors: Nguyen et al.
conference: Lecture Notes in Computer Science
year: 2019
bibkey: nguyen2019overcoming
citations: 128
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.11867'}]
tags: [RAG, Tools, Training Techniques]
---
Traditional approaches for Visual Question Answering (VQA) require large
amount of labeled data for training. Unfortunately, such large scale data is
usually not available for medical domain. In this paper, we propose a novel
medical VQA framework that overcomes the labeled data limitation. The proposed
framework explores the use of the unsupervised Denoising Auto-Encoder (DAE) and
the supervised Meta-Learning. The advantage of DAE is to leverage the large
amount of unlabeled images while the advantage of Meta-Learning is to learn
meta-weights that quickly adapt to VQA problem with limited labeled data. By
leveraging the advantages of these techniques, it allows the proposed framework
to be efficiently trained using a small labeled training set. The experimental
results show that our proposed method significantly outperforms the
state-of-the-art medical VQA.