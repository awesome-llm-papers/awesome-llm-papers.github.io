---
layout: publication
title: 'Robustness Gym: Unifying The NLP Evaluation Landscape'
authors: Goel et al.
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies: Demonstrations'
year: 2021
bibkey: goel2021robustness
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.04840'}]
tags: [Security, Distillation, Tools, Efficiency And Optimization, Evaluation, ACL,
  NAACL, Datasets, Reinforcement Learning]
---
Despite impressive performance on standard benchmarks, deep neural networks
are often brittle when deployed in real-world systems. Consequently, recent
research has focused on testing the robustness of such models, resulting in a
diverse set of evaluation methodologies ranging from adversarial attacks to
rule-based data transformations. In this work, we identify challenges with
evaluating NLP systems and propose a solution in the form of Robustness Gym
(RG), a simple and extensible evaluation toolkit that unifies 4 standard
evaluation paradigms: subpopulations, transformations, evaluation sets, and
adversarial attacks. By providing a common platform for evaluation, Robustness
Gym enables practitioners to compare results from all 4 evaluation paradigms
with just a few clicks, and to easily develop and share novel evaluation
methods using a built-in set of abstractions. To validate Robustness Gym's
utility to practitioners, we conducted a real-world case study with a
sentiment-modeling team, revealing performance degradations of 18%+. To verify
that Robustness Gym can aid novel research analyses, we perform the first study
of state-of-the-art commercial and academic named entity linking (NEL) systems,
as well as a fine-grained analysis of state-of-the-art summarization models.
For NEL, commercial systems struggle to link rare entities and lag their
academic counterparts by 10%+, while state-of-the-art summarization models
struggle on examples that require abstraction and distillation, degrading by
9%+. Robustness Gym can be found at https://robustnessgym.com/