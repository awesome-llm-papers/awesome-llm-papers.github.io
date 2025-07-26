---
layout: publication
title: Improved Text Classification Via Contrastive Adversarial Training
authors: Lin Pan, Chung-wei Hang, Avirup Sil, Saloni Potdar
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2022
bibkey: pan2021improved
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.10137'}]
tags: ["AAAI", "Evaluation", "Fine-Tuning", "Training Techniques"]
short_authors: Pan et al.
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