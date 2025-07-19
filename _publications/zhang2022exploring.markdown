---
layout: publication
title: Exploring Transformer Backbones For Heterogeneous Treatment Effect Estimation
authors: Zhang et al.
conference: Lecture Notes in Computer Science
year: 2022
bibkey: zhang2022exploring
citations: 450
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.01336'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Security]
---
Previous works on Treatment Effect Estimation (TEE) are not in widespread use
because they are predominantly theoretical, where strong parametric assumptions
are made but untractable for practical application. Recent work uses multilayer
perceptron (MLP) for modeling casual relationships, however, MLPs lag far
behind recent advances in ML methodology, which limits their applicability and
generalizability. To extend beyond the single domain formulation and towards
more realistic learning scenarios, we explore model design spaces beyond MLPs,
i.e., transformer backbones, which provide flexibility where attention layers
govern interactions among treatments and covariates to exploit structural
similarities of potential outcomes for confounding control. Through careful
model design, Transformers as Treatment Effect Estimators (TransTEE) is
proposed. We show empirically that TransTEE can: (1) serve as a general purpose
treatment effect estimator that significantly outperforms competitive baselines
in a variety of challenging TEE problems (e.g., discrete, continuous,
structured, or dosage-associated treatments) and is applicable to both when
covariates are tabular and when they consist of structural data (e.g., texts,
graphs); (2) yield multiple advantages: compatibility with propensity score
modeling, parameter efficiency, robustness to continuous treatment value
distribution shifts, explainable in covariate adjustment, and real-world
utility in auditing pre-trained language models