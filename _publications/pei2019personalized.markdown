---
layout: publication
title: Personalized Re-ranking For Recommendation
authors: Pei et al.
conference: Proceedings of the 13th ACM Conference on Recommender Systems
year: 2019
bibkey: pei2019personalized
citations: 168
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.06813'}]
tags: [Model Architecture, RecSys, Evaluation, Transformer, Datasets, Reinforcement
    Learning, Attention Mechanism]
---
Ranking is a core task in recommender systems, which aims at providing an
ordered list of items to users. Typically, a ranking function is learned from
the labeled dataset to optimize the global performance, which produces a
ranking score for each individual item. However, it may be sub-optimal because
the scoring function applies to each item individually and does not explicitly
consider the mutual influence between items, as well as the differences of
users' preferences or intents. Therefore, we propose a personalized re-ranking
model for recommender systems. The proposed re-ranking model can be easily
deployed as a follow-up modular after any ranking algorithm, by directly using
the existing ranking feature vectors. It directly optimizes the whole
recommendation list by employing a transformer structure to efficiently encode
the information of all items in the list. Specifically, the Transformer applies
a self-attention mechanism that directly models the global relationships
between any pair of items in the whole list. We confirm that the performance
can be further improved by introducing pre-trained embedding to learn
personalized encoding functions for different users. Experimental results on
both offline benchmarks and real-world online e-commerce systems demonstrate
the significant improvements of the proposed re-ranking model.