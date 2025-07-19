---
layout: publication
title: Learning To Deceive With Attention-based Explanations
authors: Pruthi et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: pruthi2019learning
citations: 154
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.07913'}]
tags: [Ethics And Bias, Model Architecture, Interpretability And Explainability, Training
    Techniques, ACL, Responsible AI, Fairness, Transformer, Bias Mitigation, Attention
    Mechanism]
---
Attention mechanisms are ubiquitous components in neural architectures
applied to natural language processing. In addition to yielding gains in
predictive accuracy, attention weights are often claimed to confer
interpretability, purportedly useful both for providing insights to
practitioners and for explaining why a model makes its decisions to
stakeholders. We call the latter use of attention mechanisms into question by
demonstrating a simple method for training models to produce deceptive
attention masks. Our method diminishes the total weight assigned to designated
impermissible tokens, even when the models can be shown to nevertheless rely on
these features to drive predictions. Across multiple models and tasks, our
approach manipulates attention weights while paying surprisingly little cost in
accuracy. Through a human study, we show that our manipulated attention-based
explanations deceive people into thinking that predictions from a model biased
against gender minorities do not rely on the gender. Consequently, our results
cast doubt on attention's reliability as a tool for auditing algorithms in the
context of fairness and accountability.