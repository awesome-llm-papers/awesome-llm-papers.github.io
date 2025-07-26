---
layout: publication
title: Towards Debiasing NLU Models From Unknown Biases
authors: Prasetya Ajie Utama, Nafise Sadat Moosavi, Iryna Gurevych
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: utama2020towards
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.12303'}]
tags: ["EMNLP", "Ethics & Fairness", "Evaluation"]
short_authors: Prasetya Ajie Utama, Nafise Sadat Moosavi, Iryna Gurevych
---
NLU models often exploit biases to achieve high dataset-specific performance
without properly learning the intended task. Recently proposed debiasing
methods are shown to be effective in mitigating this tendency. However, these
methods rely on a major assumption that the types of bias should be known
a-priori, which limits their application to many NLU tasks and datasets. In
this work, we present the first step to bridge this gap by introducing a
self-debiasing framework that prevents models from mainly utilizing biases
without knowing them in advance. The proposed framework is general and
complementary to the existing debiasing methods. We show that it allows these
existing methods to retain the improvement on the challenge datasets (i.e.,
sets of examples designed to expose models' reliance on biases) without
specifically targeting certain biases. Furthermore, the evaluation suggests
that applying the framework results in improved overall robustness.