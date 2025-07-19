---
layout: publication
title: 'Cortx: Contrastive Framework For Real-time Explanation'
authors: Chuang et al.
conference: Royal Institute of Philosophy Supplement
year: 2023
bibkey: chuang2023cortx
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.02794'}]
tags: [Interpretability And Explainability, Training Techniques, Tools, Efficiency
    And Optimization, Reinforcement Learning, Applications, Datasets]
---
Recent advancements in explainable machine learning provide effective and
faithful solutions for interpreting model behaviors. However, many explanation
methods encounter efficiency issues, which largely limit their deployments in
practical scenarios. Real-time explainer (RTX) frameworks have thus been
proposed to accelerate the model explanation process by learning a
one-feed-forward explainer. Existing RTX frameworks typically build the
explainer under the supervised learning paradigm, which requires large amounts
of explanation labels as the ground truth. Considering that accurate
explanation labels are usually hard to obtain due to constrained computational
resources and limited human efforts, effective explainer training is still
challenging in practice. In this work, we propose a COntrastive Real-Time
eXplanation (CoRTX) framework to learn the explanation-oriented representation
and relieve the intensive dependence of explainer training on explanation
labels. Specifically, we design a synthetic strategy to select positive and
negative instances for the learning of explanation. Theoretical analysis show
that our selection strategy can benefit the contrastive learning process on
explanation tasks. Experimental results on three real-world datasets further
demonstrate the efficiency and efficacy of our proposed CoRTX framework.