---
layout: publication
title: Propositional Logic For Probing Generalization In Neural Networks
authors: Langedijk Anna, Jumelet Jaap, Zuidema Willem
conference: Neural Computation
year: 2025
bibkey: langedijk2025propositional
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.08978'}]
tags: [Training Techniques, Ethics And Bias, Transformer, Model Architecture, Reinforcement
    Learning, Datasets]
---
The extent to which neural networks are able to acquire and represent symbolic rules remains a key topic of research and debate. Much current work focuses on the impressive capabilities of large language models, as well as their often ill-understood failures on a wide range of reasoning tasks. In this paper, in contrast, we investigate the generalization behavior of three key neural architectures (Transformers, Graph Convolution Networks and LSTMs) in a controlled task rooted in propositional logic. The task requires models to generate satisfying assignments for logical formulas, making it a structured and interpretable setting for studying compositionality. We introduce a balanced extension of an existing dataset to eliminate superficial patterns and enable testing on unseen operator combinations. Using this dataset, we evaluate the ability of the three architectures to generalize beyond the training distribution. While all models perform well in-distribution, we find that generalization to unseen patterns, particularly those involving negation, remains a significant challenge. Transformers fail to apply negation compositionally, unless structural biases are introduced. Our findings highlight persistent limitations in the ability of standard architectures to learn systematic representations of logical operators, suggesting the need for stronger inductive biases to support robust rule-based reasoning.