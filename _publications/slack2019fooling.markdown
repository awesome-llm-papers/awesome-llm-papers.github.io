---
layout: publication
title: 'Fooling LIME And SHAP: Adversarial Attacks On Post Hoc Explanation Methods'
authors: Slack et al.
conference: Arxiv
year: 2019
bibkey: slack2019fooling
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02508'}]
tags: [Interpretability And Explainability, RAG, Alt, Tools, Evaluation, Ethics And
    Bias, Reinforcement Learning, Security, Datasets]
---
As machine learning black boxes are increasingly being deployed in domains
such as healthcare and criminal justice, there is growing emphasis on building
tools and techniques for explaining these black boxes in an interpretable
manner. Such explanations are being leveraged by domain experts to diagnose
systematic errors and underlying biases of black boxes. In this paper, we
demonstrate that post hoc explanations techniques that rely on input
perturbations, such as LIME and SHAP, are not reliable. Specifically, we
propose a novel scaffolding technique that effectively hides the biases of any
given classifier by allowing an adversarial entity to craft an arbitrary
desired explanation. Our approach can be used to scaffold any biased classifier
in such a way that its predictions on the input data distribution still remain
biased, but the post hoc explanations of the scaffolded classifier look
innocuous. Using extensive evaluation with multiple real-world datasets
(including COMPAS), we demonstrate how extremely biased (racist) classifiers
crafted by our framework can easily fool popular explanation techniques such as
LIME and SHAP into generating innocuous explanations which do not reflect the
underlying biases.