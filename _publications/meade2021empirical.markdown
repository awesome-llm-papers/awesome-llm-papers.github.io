---
layout: publication
title: An Empirical Survey Of The Effectiveness Of Debiasing Techniques For Pre-trained
  Language Models
authors: Meade Nicholas, Poole-dayan Elinor, Reddy Siva
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2021
bibkey: meade2021empirical
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08527'}]
tags: [Ethics And Bias, Model Architecture, Survey Paper, Language Modeling, Evaluation,
  ACL, Datasets, Bias Mitigation, Attention Mechanism]
---
Recent work has shown pre-trained language models capture social biases from
the large amounts of text they are trained on. This has attracted attention to
developing techniques that mitigate such biases. In this work, we perform an
empirical survey of five recently proposed bias mitigation techniques:
Counterfactual Data Augmentation (CDA), Dropout, Iterative Nullspace
Projection, Self-Debias, and SentenceDebias. We quantify the effectiveness of
each technique using three intrinsic bias benchmarks while also measuring the
impact of these techniques on a model's language modeling ability, as well as
its performance on downstream NLU tasks. We experimentally find that: (1)
Self-Debias is the strongest debiasing technique, obtaining improved scores on
all bias benchmarks; (2) Current debiasing techniques perform less consistently
when mitigating non-gender biases; And (3) improvements on bias benchmarks such
as StereoSet and CrowS-Pairs by using debiasing strategies are often
accompanied by a decrease in language modeling ability, making it difficult to
determine whether the bias mitigation was effective.