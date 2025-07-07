---
layout: publication
title: 'Inpars: Data Augmentation For Information Retrieval Using Large Language Models'
authors: Luiz Bonifacio, Hugo Abonizio, Marzieh Fadaee, Rodrigo Nogueira
conference: Arxiv
year: 2022
citations: 20
bibkey: bonifacio2022data
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.05144'}, {name: Code,
    url: 'https://github.com/zetaalphavector/inpars'}]
tags: [Training Techniques, Transformer, Fine-Tuning, Few-Shot, Reinforcement Learning,
  Has Code, Model Architecture]
---
The information retrieval community has recently witnessed a revolution due
to large pretrained transformer models. Another key ingredient for this
revolution was the MS MARCO dataset, whose scale and diversity has enabled
zero-shot transfer learning to various tasks. However, not all IR tasks and
domains can benefit from one single dataset equally. Extensive research in
various NLP tasks has shown that using domain-specific training data, as
opposed to a general-purpose one, improves the performance of neural models. In
this work, we harness the few-shot capabilities of large pretrained language
models as synthetic data generators for IR tasks. We show that models finetuned
solely on our unsupervised dataset outperform strong baselines such as BM25 as
well as recently proposed self-supervised dense retrieval methods. Furthermore,
retrievers finetuned on both supervised and our synthetic data achieve better
zero-shot transfer than models finetuned only on supervised data. Code, models,
and data are available at https://github.com/zetaalphavector/inpars .