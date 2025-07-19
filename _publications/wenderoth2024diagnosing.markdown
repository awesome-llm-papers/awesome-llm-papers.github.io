---
layout: publication
title: Diagnosing Medical Datasets With Training Dynamics
authors: Wenderoth Laura
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: wenderoth2024diagnosing
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.01653'}]
tags: [Training Techniques, EMNLP, Alt, Tools, Evaluation, Datasets]
---
This study explores the potential of using training dynamics as an automated
alternative to human annotation for evaluating the quality of training data.
The framework used is Data Maps, which classifies data points into categories
such as easy-to-learn, hard-to-learn, and ambiguous (Swayamdipta et al., 2020).
Swayamdipta et al. (2020) highlight that difficult-to-learn examples often
contain errors, and ambiguous cases significantly impact model training. To
confirm the reliability of these findings, we replicated the experiments using
a challenging dataset, with a focus on medical question answering. In addition
to text comprehension, this field requires the acquisition of detailed medical
knowledge, which further complicates the task. A comprehensive evaluation was
conducted to assess the feasibility and transferability of the Data Maps
framework to the medical domain. The evaluation indicates that the framework is
unsuitable for addressing datasets' unique challenges in answering medical
questions.