---
layout: publication
title: 'Generate, Annotate, And Learn: NLP With Synthetic Text'
authors: Xuanli He, Islam Nassar, Jamie Kiros, Gholamreza Haffari, Mohammad Norouzi
conference: Arxiv
year: 2021
citations: 17
bibkey: he2021nlp
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.06168'}]
tags: [Distillation, Transformer, Training Techniques, Few-Shot, Tools, Efficiency
    and Optimization, Applications, Prompting, Model Architecture]
---
This paper studies the use of language models as a source of synthetic
unlabeled text for NLP. We formulate a general framework called ``generate,
annotate, and learn (GAL)'' to take advantage of synthetic text within
knowledge distillation, self-training, and few-shot learning applications. To
generate high-quality task-specific text, we either fine-tune LMs on inputs
from the task of interest, or prompt large LMs with few examples. We use the
best available classifier to annotate synthetic text with soft pseudo labels
for knowledge distillation and self-training, and use LMs to obtain hard labels
for few-shot learning. We train new supervised models on the combination of
labeled and pseudo-labeled data, which results in significant gains across
several applications. We investigate key components of GAL and present
theoretical and empirical arguments against the use of class-conditional LMs to
generate synthetic labeled text instead of unlabeled text. GAL achieves new
state-of-the-art knowledge distillation results for 6-layer transformers on the
GLUE leaderboard.