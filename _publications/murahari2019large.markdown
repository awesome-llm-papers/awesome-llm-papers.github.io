---
layout: publication
title: 'Large-scale Pretraining For Visual Dialog: A Simple State-of-the-art Baseline'
authors: Vishvak Murahari, Dhruv Batra, Devi Parikh, Abhishek Das
conference: Lecture Notes in Computer Science
year: 2020
bibkey: murahari2019large
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.02379'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Murahari et al.
---
Prior work in visual dialog has focused on training deep neural models on
VisDial in isolation. Instead, we present an approach to leverage pretraining
on related vision-language datasets before transferring to visual dialog. We
adapt the recently proposed ViLBERT (Lu et al., 2019) model for multi-turn
visually-grounded conversations. Our model is pretrained on the Conceptual
Captions and Visual Question Answering datasets, and finetuned on VisDial. Our
best single model outperforms prior published work (including model ensembles)
by more than 1% absolute on NDCG and MRR. Next, we find that additional
finetuning using "dense" annotations in VisDial leads to even higher NDCG --
more than 10% over our base model -- but hurts MRR -- more than 17% below our
base model! This highlights a trade-off between the two primary metrics -- NDCG
and MRR -- which we find is due to dense annotations not correlating well with
the original ground-truth answers to questions.