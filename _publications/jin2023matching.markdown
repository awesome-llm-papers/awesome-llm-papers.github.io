---
layout: publication
title: Matching Patients To Clinical Trials With Large Language Models
authors: Jin et al.
conference: Nature Communications
year: 2023
bibkey: jin2023matching
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.15051'}]
tags: [Interpretability And Explainability, GPT, Tools, Evaluation, Model Architecture,
  Reinforcement Learning]
---
Patient recruitment is challenging for clinical trials. We introduce
TrialGPT, an end-to-end framework for zero-shot patient-to-trial matching with
large language models. TrialGPT comprises three modules: it first performs
large-scale filtering to retrieve candidate trials (TrialGPT-Retrieval); then
predicts criterion-level patient eligibility (TrialGPT-Matching); and finally
generates trial-level scores (TrialGPT-Ranking). We evaluate TrialGPT on three
cohorts of 183 synthetic patients with over 75,000 trial annotations.
TrialGPT-Retrieval can recall over 90% of relevant trials using less than 6% of
the initial collection. Manual evaluations on 1,015 patient-criterion pairs
show that TrialGPT-Matching achieves an accuracy of 87.3% with faithful
explanations, close to the expert performance. The TrialGPT-Ranking scores are
highly correlated with human judgments and outperform the best-competing models
by 43.8% in ranking and excluding trials. Furthermore, our user study reveals
that TrialGPT can reduce the screening time by 42.6% in patient recruitment.
Overall, these results have demonstrated promising opportunities for
patient-to-trial matching with TrialGPT.