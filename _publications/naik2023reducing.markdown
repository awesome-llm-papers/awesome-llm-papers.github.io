---
layout: publication
title: Reducing Gender Bias In Machine Translation Through Counterfactual Data Generation
authors: Naik Ranjita, Rarrick Spencer, Chowdhary Vishal
conference: Transactions of the Association for Computational Linguistics
year: 2023
bibkey: naik2023reducing
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.16362'}]
tags: [Ethics And Bias, Training Techniques, Evaluation, TACL, ACL, RAG, Datasets]
---
Recent advances in neural methods have led to substantial improvement in the
quality of Neural Machine Translation (NMT) systems. However, these systems
frequently produce translations with inaccurate gender (Stanovsky et al.,
2019), which can be traced to bias in training data. Saunders and Byrne (2020)
tackle this problem with a handcrafted dataset containing balanced gendered
profession words. By using this data to fine-tune an existing NMT model, they
show that gender bias can be significantly mitigated, albeit at the expense of
translation quality due to catastrophic forgetting. They recover some of the
lost quality with modified training objectives or additional models at
inference. We find, however, that simply supplementing the handcrafted dataset
with a random sample from the base model training corpus is enough to
significantly reduce the catastrophic forgetting. We also propose a novel
domain-adaptation technique that leverages in-domain data created with the
counterfactual data generation techniques proposed by Zmigrod et al. (2019) to
further improve accuracy on the WinoMT challenge test set without significant
loss in translation quality. We show its effectiveness in NMT systems from
English into three morphologically rich languages French, Spanish, and Italian.
The relevant dataset and code will be available at Github.