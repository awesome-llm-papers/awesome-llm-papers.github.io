---
layout: publication
title: Document-level Relation Extraction With Adaptive Focal Loss And Knowledge Distillation
authors: Tan et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2022
bibkey: tan2022document
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.10900'}]
tags: [Model Architecture, Distillation, Tools, Training Techniques, Efficiency And
    Optimization, Evaluation, ACL, Datasets, Attention Mechanism]
---
Document-level Relation Extraction (DocRE) is a more challenging task
compared to its sentence-level counterpart. It aims to extract relations from
multiple sentences at once. In this paper, we propose a semi-supervised
framework for DocRE with three novel components. Firstly, we use an axial
attention module for learning the interdependency among entity-pairs, which
improves the performance on two-hop relations. Secondly, we propose an adaptive
focal loss to tackle the class imbalance problem of DocRE. Lastly, we use
knowledge distillation to overcome the differences between human annotated data
and distantly supervised data. We conducted experiments on two DocRE datasets.
Our model consistently outperforms strong baselines and its performance exceeds
the previous SOTA by 1.36 F1 and 1.46 Ign_F1 score on the DocRED leaderboard.
Our code and data will be released at https://github.com/tonytan48/KD-DocRE.