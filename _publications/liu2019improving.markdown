---
layout: publication
title: Improving Multi-task Deep Neural Networks Via Knowledge Distillation For Natural
  Language Understanding
authors: Xiaodong Liu, Pengcheng He, Weizhu Chen, Jianfeng Gao
conference: Arxiv
year: 2019
bibkey: liu2019improving
citations: 165
additional_links: [{name: Code, url: 'https://gluebenchmark.com/leaderboard'}, {name: Code,
    url: 'https://github.com/namisan/mt-dnn'}, {name: Paper, url: 'https://arxiv.org/abs/1904.09482'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Has Code"]
short_authors: Liu et al.
---
This paper explores the use of knowledge distillation to improve a Multi-Task
Deep Neural Network (MT-DNN) (Liu et al., 2019) for learning text
representations across multiple natural language understanding tasks. Although
ensemble learning can improve model performance, serving an ensemble of large
DNNs such as MT-DNN can be prohibitively expensive. Here we apply the knowledge
distillation method (Hinton et al., 2015) in the multi-task learning setting.
For each task, we train an ensemble of different MT-DNNs (teacher) that
outperforms any single model, and then train a single MT-DNN (student) via
multi-task learning to *distill* knowledge from these ensemble teachers.
We show that the distilled MT-DNN significantly outperforms the original MT-DNN
on 7 out of 9 GLUE tasks, pushing the GLUE benchmark (single model) to 83.7%
(1.5% absolute improvement\footnote\{ Based on the GLUE leaderboard at
https://gluebenchmark.com/leaderboard as of April 1, 2019.\}). The code and
pre-trained models will be made publicly available at
https://github.com/namisan/mt-dnn.