---
layout: publication
title: Understanding And Detecting Hallucinations In Neural Machine Translation Via
  Model Introspection
authors: Weijia Xu, Sweta Agrawal, Eleftheria Briakou, Marianna J. Martindale, Marine
  Carpuat
conference: Arxiv
year: 2023
citations: 15
bibkey: xu2023understanding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.07779'}]
tags: [Uncategorized]
---
Neural sequence generation models are known to "hallucinate", by producing
outputs that are unrelated to the source text. These hallucinations are
potentially harmful, yet it remains unclear in what conditions they arise and
how to mitigate their impact. In this work, we first identify internal model
symptoms of hallucinations by analyzing the relative token contributions to the
generation in contrastive hallucinated vs. non-hallucinated outputs generated
via source perturbations. We then show that these symptoms are reliable
indicators of natural hallucinations, by using them to design a lightweight
hallucination detector which outperforms both model-free baselines and strong
classifiers based on quality estimation or large pre-trained models on manually
annotated English-Chinese and German-English translation test beds.