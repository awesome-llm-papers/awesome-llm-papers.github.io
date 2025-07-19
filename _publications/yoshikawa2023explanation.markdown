---
layout: publication
title: Explanation-based Training With Differentiable Insertion/deletion Metric-aware
  Regularizers
authors: Yoshikawa Yuya, Iwata Tomoharu
conference: Discrete Mathematics and Applications
year: 2023
bibkey: yoshikawa2023explanation
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.12553'}]
tags: [Interpretability And Explainability, Training Techniques, Evaluation, Efficiency
    And Optimization, Applications, Datasets]
---
The quality of explanations for the predictions made by complex machine
learning predictors is often measured using insertion and deletion metrics,
which assess the faithfulness of the explanations, i.e., how accurately the
explanations reflect the predictor's behavior. To improve the faithfulness, we
propose insertion/deletion metric-aware explanation-based optimization
(ID-ExpO), which optimizes differentiable predictors to improve both the
insertion and deletion scores of the explanations while maintaining their
predictive accuracy. Because the original insertion and deletion metrics are
non-differentiable with respect to the explanations and directly unavailable
for gradient-based optimization, we extend the metrics so that they are
differentiable and use them to formalize insertion and deletion metric-based
regularizers. Our experimental results on image and tabular datasets show that
the deep neural network-based predictors that are fine-tuned using ID-ExpO
enable popular post-hoc explainers to produce more faithful and
easier-to-interpret explanations while maintaining high predictive accuracy.
The code is available at https://github.com/yuyay/idexpo.