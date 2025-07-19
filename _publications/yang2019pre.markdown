---
layout: publication
title: Pre-training Of Context-aware Item Representation For Next Basket Recommendation
authors: Yang et al.
conference: ACM Transactions on Information Systems
year: 2019
bibkey: yang2019pre
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.12604'}]
tags: [Training Techniques, BERT, Transformer, Model Architecture]
---
Next basket recommendation, which aims to predict the next a few items that a
user most probably purchases given his historical transactions, plays a vital
role in market basket analysis. From the viewpoint of item, an item could be
purchased by different users together with different items, for different
reasons. Therefore, an ideal recommender system should represent an item
considering its transaction contexts. Existing state-of-the-art deep learning
methods usually adopt the static item representations, which are invariant
among all of the transactions and thus cannot achieve the full potentials of
deep learning. Inspired by the pre-trained representations of BERT in natural
language processing, we propose to conduct context-aware item representation
for next basket recommendation, called Item Encoder Representations from
Transformers (IERT). In the offline phase, IERT pre-trains deep item
representations conditioning on their transaction contexts. In the online
recommendation phase, the pre-trained model is further fine-tuned with an
additional output layer. The output contextualized item embeddings are used to
capture users' sequential behaviors and general tastes to conduct
recommendation. Experimental results on the Ta-Feng data set show that IERT
outperforms the state-of-the-art baseline methods, which demonstrated the
effectiveness of IERT in next basket representation.