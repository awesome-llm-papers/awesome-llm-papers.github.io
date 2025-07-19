---
layout: publication
title: 'Leakage-adjusted Simulatability: Can Models Generate Non-trivial Explanations
  Of Their Behavior In Natural Language?'
authors: Hase et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: hase2020leakage
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.04119'}]
tags: [Interpretability And Explainability, Evaluation, ACL, Agentic, EMNLP, Datasets,
  Reinforcement Learning]
---
Data collection for natural language (NL) understanding tasks has
increasingly included human explanations alongside data points, allowing past
works to introduce models that both perform a task and generate NL explanations
for their outputs. Yet to date, model-generated explanations have been
evaluated on the basis of surface-level similarities to human explanations,
both through automatic metrics like BLEU and human evaluations. We argue that
these evaluations are insufficient, since they fail to indicate whether
explanations support actual model behavior (faithfulness), rather than simply
match what a human would say (plausibility). In this work, we address the
problem of evaluating explanations from the model simulatability perspective.
Our contributions are as follows: (1) We introduce a leakage-adjusted
simulatability (LAS) metric for evaluating NL explanations, which measures how
well explanations help an observer predict a model's output, while controlling
for how explanations can directly leak the output. We use a model as a proxy
for a human observer, and validate this choice with two human subject
experiments. (2) Using the CoS-E and e-SNLI datasets, we evaluate two existing
generative graphical models and two new approaches; one rationalizing method we
introduce achieves roughly human-level LAS scores. (3) Lastly, we frame
explanation generation as a multi-agent game and optimize explanations for
simulatability while penalizing label leakage, which can improve LAS scores. We
provide code for the experiments in this paper at
https://github.com/peterbhase/LAS-NL-Explanations