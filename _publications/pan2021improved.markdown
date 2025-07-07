---
layout: publication
title: Improved Text Classification Via Contrastive Adversarial Training
authors: Lin Pan, Chung-wei Hang, Avirup Sil, Saloni Potdar
conference: Arxiv
year: 2021
citations: 47
bibkey: pan2021improved
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.10137'}]
tags: [Training Techniques, Transformer, RAG, Fine-Tuning, BERT, Security, Model Architecture]
---
We propose a simple and general method to regularize the fine-tuning of
Transformer-based encoders for text classification tasks. Specifically, during
fine-tuning we generate adversarial examples by perturbing the word embeddings
of the model and perform contrastive learning on clean and adversarial examples
in order to teach the model to learn noise-invariant representations. By
training on both clean and adversarial examples along with the additional
contrastive objective, we observe consistent improvement over standard
fine-tuning on clean examples. On several GLUE benchmark tasks, our fine-tuned
BERT Large model outperforms BERT Large baseline by 1.7% on average, and our
fine-tuned RoBERTa Large improves over RoBERTa Large baseline by 1.3%. We
additionally validate our method in different domains using three intent
classification datasets, where our fine-tuned RoBERTa Large outperforms RoBERTa
Large baseline by 1-2% on average.