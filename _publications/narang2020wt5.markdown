---
layout: publication
title: WT5?! Training Text-to-text Models To Explain Their Predictions
authors: Sharan Narang, Colin Raffel, Katherine Lee, Adam Roberts, Noah Fiedel, Karishma
  Malkan
conference: Arxiv
year: 2020
bibkey: narang2020wt5
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14546'}]
tags: ["Training Techniques"]
short_authors: Narang et al.
---
Neural networks have recently achieved human-level performance on various
challenging natural language processing (NLP) tasks, but it is notoriously
difficult to understand why a neural network produced a particular prediction.
In this paper, we leverage the text-to-text framework proposed by Raffel et
al.(2019) to train language models to output a natural text explanation
alongside their prediction. Crucially, this requires no modifications to the
loss function or training and decoding procedures -- we simply train the model
to output the explanation after generating the (natural text) prediction. We
show that this approach not only obtains state-of-the-art results on
explainability benchmarks, but also permits learning from a limited set of
labeled explanations and transferring rationalization abilities across
datasets. To facilitate reproducibility and future work, we release our code
use to train the models.