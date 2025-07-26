---
layout: publication
title: 'Berts Of A Feather Do Not Generalize Together: Large Variability In Generalization
  Across Models With Similar Test Set Performance'
authors: R. Thomas Mccoy, Junghyun Min, Tal Linzen
conference: Proceedings of the Third BlackboxNLP Workshop on Analyzing and Interpreting
  Neural Networks for NLP
year: 2020
bibkey: mccoy2019berts
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02969'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: R. Thomas Mccoy, Junghyun Min, Tal Linzen
---
If the same neural network architecture is trained multiple times on the same
dataset, will it make similar linguistic generalizations across runs? To study
this question, we fine-tuned 100 instances of BERT on the Multi-genre Natural
Language Inference (MNLI) dataset and evaluated them on the HANS dataset, which
evaluates syntactic generalization in natural language inference. On the MNLI
development set, the behavior of all instances was remarkably consistent, with
accuracy ranging between 83.6% and 84.8%. In stark contrast, the same models
varied widely in their generalization performance. For example, on the simple
case of subject-object swap (e.g., determining that "the doctor visited the
lawyer" does not entail "the lawyer visited the doctor"), accuracy ranged from
0.00% to 66.2%. Such variation is likely due to the presence of many local
minima that are equally attractive to a low-bias learner such as a neural
network; decreasing the variability may therefore require models with stronger
inductive biases.