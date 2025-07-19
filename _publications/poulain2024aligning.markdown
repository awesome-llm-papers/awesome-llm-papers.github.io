---
layout: publication
title: Aligning (medical) Llms For (counterfactual) Fairness
authors: Poulain Raphael, Fayyaz Hamed, Beheshti Rahmatollah
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: poulain2024aligning
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.12055'}]
tags: [Fairness, Distillation, Alt, Bias Mitigation, Tools, Evaluation, Ethics And
    Bias, Efficiency And Optimization, Reinforcement Learning, Applications, AAAI]
---
Large Language Models (LLMs) have emerged as promising solutions for a
variety of medical and clinical decision support applications. However, LLMs
are often subject to different types of biases, which can lead to unfair
treatment of individuals, worsening health disparities, and reducing trust in
AI-augmented medical tools. Aiming to address this important issue, in this
study, we present a new model alignment approach for aligning LLMs using a
preference optimization method within a knowledge distillation framework. Prior
to presenting our proposed method, we first use an evaluation framework to
conduct a comprehensive (largest to our knowledge) empirical evaluation to
reveal the type and nature of existing biases in LLMs used for medical
applications. We then offer a bias mitigation technique to reduce the unfair
patterns in LLM outputs across different subgroups identified by the protected
attributes. We show that our mitigation method is effective in significantly
reducing observed biased patterns. Our code is publicly available at
https://github.com/healthylaife/FairAlignmentLLM.