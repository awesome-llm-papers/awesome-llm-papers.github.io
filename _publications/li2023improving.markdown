---
layout: publication
title: Improving Sequential Recommendation Models With An Enhanced Loss Function
authors: Li et al.
conference: The 41st International ACM SIGIR Conference on Research &amp; Development
  in Information Retrieval
year: 2023
bibkey: li2023improving
citations: 308
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.00979'}]
tags: [Interpretability And Explainability, RAG, Training Techniques, Evaluation,
  BERT, Model Architecture, SIGIR, Datasets]
---
There has been a growing interest in benchmarking sequential recommendation
models and reproducing/improving existing models. For example, Rendle et al.
improved matrix factorization models by tuning their parameters and
hyperparameters. Petrov and Macdonald developed a more efficient and effective
implementation of BERT4Rec, which resolved inconsistencies in performance
comparison between BERT4Rec and SASRec in previous works. In particular,
BERT4Rec and SASRec share a similar network structure, with the main difference
lying in their training objective/loss function. Therefore, we analyzed the
advantages and disadvantages of commonly used loss functions in sequential
recommendation and proposed an improved loss function that leverages their
strengths. We conduct extensive experiments on two influential open-source
libraries, and the results demonstrate that our improved loss function
significantly enhances the performance of GRU4Rec, SASRec, SR-GNN, and S3Rec
models, improving their benchmarks significantly. Furthermore, the improved
SASRec benchmark outperforms BERT4Rec on the ML-1M and Beauty datasets and
achieves similar results to BERT4Rec on the ML-20M and Steam datasets. We also
reproduce the results of the BERT4Rec model on the Beauty dataset. Finally, we
provide a comprehensive explanation of the effectiveness of our improved loss
function through experiments. Our code is publicly available at
https://github.com/Li-fAngyU/sequential_rec.