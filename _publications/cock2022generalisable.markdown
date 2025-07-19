---
layout: publication
title: Generalisable Methods For Early Prediction In Interactive Simulations For Education
authors: Cock et al.
conference: JMIR Medical Education
year: 2022
bibkey: cock2022generalisable
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.01457'}]
tags: [Interpretability And Explainability, Attention Mechanism, Model Architecture,
  Reinforcement Learning, Fine Tuning]
---
Interactive simulations allow students to discover the underlying principles
of a scientific phenomenon through their own exploration. Unfortunately,
students often struggle to learn effectively in these environments. Classifying
students' interaction data in the simulations based on their expected
performance has the potential to enable adaptive guidance and consequently
improve students' learning. Previous research in this field has mainly focused
on a-posteriori analyses or investigations limited to one specific predictive
model and simulation. In this paper, we investigate the quality and
generalisability of models for an early prediction of conceptual understanding
based on clickstream data of students across interactive simulations. We first
measure the students' conceptual understanding through their in-task
performance. Then, we suggest a novel type of features that, starting from
clickstream data, encodes both the state of the simulation and the action
performed by the student. We finally propose to feed these features into
GRU-based models, with and without attention, for prediction. Experiments on
two different simulations and with two different populations show that our
proposed models outperform shallow learning baselines and better generalise to
different learning environments and populations. The inclusion of attention
into the model increases interpretability in terms of effective inquiry. The
source code is available on Github
(https://github.com/epfl-ml4ed/beerslaw-lab.git).