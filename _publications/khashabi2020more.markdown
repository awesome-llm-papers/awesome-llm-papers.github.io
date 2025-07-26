---
layout: publication
title: 'More Bang For Your Buck: Natural Perturbation For Robust Question Answering'
authors: Daniel Khashabi, Tushar Khot, Ashish Sabharwal
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: khashabi2020more
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.04849'}]
tags: ["EMNLP"]
short_authors: Daniel Khashabi, Tushar Khot, Ashish Sabharwal
---
While recent models have achieved human-level scores on many NLP datasets, we
observe that they are considerably sensitive to small changes in input. As an
alternative to the standard approach of addressing this issue by constructing
training sets of completely new examples, we propose doing so via minimal
perturbation of examples. Specifically, our approach involves first collecting
a set of seed examples and then applying human-driven natural perturbations (as
opposed to rule-based machine perturbations), which often change the gold label
as well. Local perturbations have the advantage of being relatively easier (and
hence cheaper) to create than writing out completely new examples. To evaluate
the impact of this phenomenon, we consider a recent question-answering dataset
(BoolQ) and study the benefit of our approach as a function of the perturbation
cost ratio, the relative cost of perturbing an existing question vs. creating a
new one from scratch. We find that when natural perturbations are moderately
cheaper to create, it is more effective to train models using them: such models
exhibit higher robustness and better generalization, while retaining
performance on the original BoolQ dataset.