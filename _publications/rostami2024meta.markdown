---
layout: publication
title: 'Meta-task: A Method-agnostic Framework For Learning To Regularize In Few-shot
  Learning'
authors: Rostami et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: rostami2024meta
citations: 330
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.18599'}]
tags: [RAG, Tools, Evaluation, CVPR, Few Shot, Efficiency And Optimization, Reinforcement
    Learning, Datasets]
---
Overfitting is a significant challenge in Few-Shot Learning (FSL), where
models trained on small, variable datasets tend to memorize rather than
generalize to unseen tasks. Regularization is crucial in FSL to prevent
overfitting and enhance generalization performance. To address this issue, we
introduce Meta-Task, a novel, method-agnostic framework that leverages both
labeled and unlabeled data to enhance generalization through auxiliary tasks
for regularization. Specifically, Meta-Task introduces a Task-Decoder, which is
a simple example of the broader framework that refines hidden representations
by reconstructing input images from embeddings, effectively mitigating
overfitting.
  Our framework's method-agnostic design ensures its broad applicability across
various FSL settings. We validate Meta-Task's effectiveness on standard
benchmarks, including Mini-ImageNet, Tiered-ImageNet, and FC100, where it
consistently improves existing state-of-the-art meta-learning techniques,
demonstrating superior performance, faster convergence, reduced generalization
error, and lower variance-all without extensive hyperparameter tuning. These
results underline Meta-Task's practical applicability and efficiency in
real-world, resource-constrained scenarios.