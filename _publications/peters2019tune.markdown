---
layout: publication
title: To Tune Or Not To Tune? Adapting Pretrained Representations To Diverse Tasks
authors: Peters Matthew E., Ruder Sebastian, Smith Noah A.
conference: Proceedings of the 4th Workshop on Representation Learning for NLP (RepL4NLP-2019)
year: 2019
bibkey: peters2019tune
citations: 394
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.05987'}]
tags: [Fine Tuning, Model Architecture, Training Techniques, Interpretability And
    Explainability]
---
While most previous work has focused on different pretraining objectives and
architectures for transfer learning, we ask how to best adapt the pretrained
model to a given target task. We focus on the two most common forms of
adaptation, feature extraction (where the pretrained weights are frozen), and
directly fine-tuning the pretrained model. Our empirical results across diverse
NLP tasks with two state-of-the-art models show that the relative performance
of fine-tuning vs. feature extraction depends on the similarity of the
pretraining and target tasks. We explore possible explanations for this finding
and provide a set of adaptation guidelines for the NLP practitioner.