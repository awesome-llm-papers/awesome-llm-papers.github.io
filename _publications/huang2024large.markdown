---
layout: publication
title: Large Language Model Pruning
authors: Huang Hanjuan, Song Hao-jia, Pao Hsing-kuo
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: huang2024large
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.00030'}]
tags: [Interpretability And Explainability, EMNLP, Attention Mechanism, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Pruning]
---
We surely enjoy the larger the better models for their superior performance
in the last couple of years when both the hardware and software support the
birth of such extremely huge models. The applied fields include text mining and
others. In particular, the success of LLMs on text understanding and text
generation draws attention from researchers who have worked on NLP and related
areas for years or even decades. On the side, LLMs may suffer from problems
like model overfitting, hallucination, and device limitation to name a few. In
this work, we suggest a model pruning technique specifically focused on LLMs.
The proposed methodology emphasizes the explainability of deep learning models.
By having the theoretical foundation, we obtain a trustworthy deep model so
that huge models with a massive number of model parameters become not quite
necessary. A mutual information-based estimation is adopted to find neurons
with redundancy to eliminate. Moreover, an estimator with well-tuned parameters
helps to find precise estimation to guide the pruning procedure. At the same
time, we also explore the difference between pruning on large-scale models vs.
pruning on small-scale models. The choice of pruning criteria is sensitive in
small models but not for large-scale models. It is a novel finding through this
work. Overall, we demonstrate the superiority of the proposed model to the
state-of-the-art models.