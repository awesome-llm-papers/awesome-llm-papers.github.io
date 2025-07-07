---
layout: publication
title: Language Model Compression With Weighted Low-rank Factorization
authors: Yen-chang Hsu et al.
conference: Arxiv
year: 2022
citations: 16
bibkey: hsu2022language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.00112'}]
tags: [Training Techniques, Transformer, Pre-Training, Efficiency and Optimization,
  Model Architecture, Quantization]
---
Factorizing a large matrix into small matrices is a popular strategy for
model compression. Singular value decomposition (SVD) plays a vital role in
this compression strategy, approximating a learned matrix with fewer
parameters. However, SVD minimizes the squared error toward reconstructing the
original matrix without gauging the importance of the parameters, potentially
giving a larger reconstruction error for those who affect the task accuracy
more. In other words, the optimization objective of SVD is not aligned with the
trained model's task accuracy. We analyze this previously unexplored problem,
make observations, and address it by introducing Fisher information to weigh
the importance of parameters affecting the model prediction. This idea leads to
our method: Fisher-Weighted SVD (FWSVD). Although the factorized matrices from
our approach do not result in smaller reconstruction errors, we find that our
resulting task accuracy is much closer to the original model's performance. We
perform analysis with the transformer-based language models, showing our
weighted SVD largely alleviates the mismatched optimization objectives and can
maintain model performance with a higher compression rate. Our method can
directly compress a task-specific model while achieving better performance than
other compact model strategies requiring expensive model pre-training.
Moreover, the evaluation of compressing an already compact model shows our
method can further reduce 9% to 30% parameters with an insignificant impact on
task accuracy.