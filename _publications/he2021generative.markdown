---
layout: publication
title: 'GALAXY: A Generative Pre-trained Model For Task-oriented Dialog With Semi-supervised
  Learning And Explicit Policy Injection'
authors: Wanwei He et al.
conference: Arxiv
year: 2021
citations: 37
bibkey: he2021generative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.14592'}]
tags: [Efficiency and Optimization, Pre-Training, Training Techniques, Few-Shot]
---
Pre-trained models have proved to be powerful in enhancing task-oriented
dialog systems. However, current pre-training methods mainly focus on enhancing
dialog understanding and generation tasks while neglecting the exploitation of
dialog policy. In this paper, we propose GALAXY, a novel pre-trained dialog
model that explicitly learns dialog policy from limited labeled dialogs and
large-scale unlabeled dialog corpora via semi-supervised learning.
Specifically, we introduce a dialog act prediction task for policy optimization
during pre-training and employ a consistency regularization term to refine the
learned representation with the help of unlabeled dialogs. We also implement a
gating mechanism to weigh suitable unlabeled dialog samples. Empirical results
show that GALAXY substantially improves the performance of task-oriented dialog
systems, and achieves new state-of-the-art results on benchmark datasets:
In-Car, MultiWOZ2.0 and MultiWOZ2.1, improving their end-to-end combined scores
by 2.5, 5.3 and 5.5 points, respectively. We also show that GALAXY has a
stronger few-shot ability than existing models under various low-resource
settings.