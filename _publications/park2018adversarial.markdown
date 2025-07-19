---
layout: publication
title: Adversarial Sampling And Training For Semi-supervised Information Retrieval
authors: Park Dae Hoon, Chang Yi
conference: The World Wide Web Conference
year: 2018
bibkey: park2018adversarial
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.04155'}]
tags: [Training Techniques, Tools, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Security, Datasets]
---
Ad-hoc retrieval models with implicit feedback often have problems, e.g., the
imbalanced classes in the data set. Too few clicked documents may hurt
generalization ability of the models, whereas too many non-clicked documents
may harm effectiveness of the models and efficiency of training. In addition,
recent neural network-based models are vulnerable to adversarial examples due
to the linear nature in them. To solve the problems at the same time, we
propose an adversarial sampling and training framework to learn ad-hoc
retrieval models with implicit feedback. Our key idea is (i) to augment clicked
examples by adversarial training for better generalization and (ii) to obtain
very informational non-clicked examples by adversarial sampling and training.
Experiments are performed on benchmark data sets for common ad-hoc retrieval
tasks such as Web search, item recommendation, and question answering.
Experimental results indicate that the proposed approaches significantly
outperform strong baselines especially for high-ranked documents, and they
outperform IRGAN in NDCG@5 using only 5% of labeled data for the Web search
task.