---
layout: publication
title: Generating Effective Ensembles For Sentiment Analysis
authors: Etelis et al.
conference: Decision Support Systems
year: 2024
bibkey: etelis2024generating
citations: 311
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.16700'}]
tags: [GPT, Evaluation, Transformer, Model Architecture, Reinforcement Learning, Datasets,
  Merging]
---
In recent years, transformer models have revolutionized Natural Language
Processing (NLP), achieving exceptional results across various tasks, including
Sentiment Analysis (SA). As such, current state-of-the-art approaches for SA
predominantly rely on transformer models alone, achieving impressive accuracy
levels on benchmark datasets. In this paper, we show that the key for further
improving the accuracy of such ensembles for SA is to include not only
transformers, but also traditional NLP models, despite the inferiority of the
latter compared to transformer models. However, as we empirically show, this
necessitates a change in how the ensemble is constructed, specifically relying
on the Hierarchical Ensemble Construction (HEC) algorithm we present. Our
empirical studies across eight canonical SA datasets reveal that ensembles
incorporating a mix of model types, structured via HEC, significantly
outperform traditional ensembles. Finally, we provide a comparative analysis of
the performance of the HEC and GPT-4, demonstrating that while GPT-4 closely
approaches state-of-the-art SA methods, it remains outperformed by our proposed
ensemble strategy.