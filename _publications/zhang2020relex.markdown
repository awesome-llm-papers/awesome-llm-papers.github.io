---
layout: publication
title: 'Relex: A Model-agnostic Relational Model Explainer'
authors: Yue Zhang, David Defazio, Arti Ramesh
conference: Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society
year: 2021
bibkey: zhang2020relex
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.00305'}]
tags: ["AAAI", "Ethics & Fairness"]
short_authors: Yue Zhang, David Defazio, Arti Ramesh
---
In recent years, considerable progress has been made on improving the
interpretability of machine learning models. This is essential, as complex deep
learning models with millions of parameters produce state of the art results,
but it can be nearly impossible to explain their predictions. While various
explainability techniques have achieved impressive results, nearly all of them
assume each data instance to be independent and identically distributed (iid).
This excludes relational models, such as Statistical Relational Learning (SRL),
and the recently popular Graph Neural Networks (GNNs), resulting in few options
to explain them. While there does exist one work on explaining GNNs,
GNN-Explainer, they assume access to the gradients of the model to learn
explanations, which is restrictive in terms of its applicability across
non-differentiable relational models and practicality. In this work, we develop
RelEx, a model-agnostic relational explainer to explain black-box relational
models with only access to the outputs of the black-box. RelEx is able to
explain any relational model, including SRL models and GNNs. We compare RelEx
to the state-of-the-art relational explainer, GNN-Explainer, and relational
extensions of iid explanation models and show that RelEx achieves comparable or
better performance, while remaining model-agnostic.