---
layout: publication
title: 'Adversarial Tableqa: Attention Supervision For Question Answering On Tables'
authors: Cho et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: cho2018adversarial
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.08113'}]
tags: [Interpretability And Explainability, Attention Mechanism, Tools, Evaluation,
  Model Architecture, Security, AAAI, Datasets]
---
The task of answering a question given a text passage has shown great
developments on model performance thanks to community efforts in building
useful datasets. Recently, there have been doubts whether such rapid progress
has been based on truly understanding language. The same question has not been
asked in the table question answering (TableQA) task, where we are tasked to
answer a query given a table. We show that existing efforts, of using "answers"
for both evaluation and supervision for TableQA, show deteriorating
performances in adversarial settings of perturbations that do not affect the
answer. This insight naturally motivates to develop new models that understand
question and table more precisely. For this goal, we propose Neural Operator
(NeOp), a multi-layer sequential network with attention supervision to answer
the query given a table. NeOp uses multiple Selective Recurrent Units (SelRUs)
to further help the interpretability of the answers of the model. Experiments
show that the use of operand information to train the model significantly
improves the performance and interpretability of TableQA models. NeOp
outperforms all the previous models by a big margin.