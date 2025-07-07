---
layout: publication
title: What To Pre-train On? Efficient Intermediate Task Selection
authors: "Clifton Poth, Jonas Pfeiffer, Andreas R\xFCckl\xE9, Iryna Gurevych"
conference: Arxiv
year: 2021
citations: 15
bibkey: poth2021what
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08247'}]
tags: [RAG, Few-Shot, Training Techniques, Fine-Tuning]
---
Intermediate task fine-tuning has been shown to culminate in large transfer
gains across many NLP tasks. With an abundance of candidate datasets as well as
pre-trained language models, it has become infeasible to run the cross-product
of all combinations to find the best transfer setting. In this work we first
establish that similar sequential fine-tuning gains can be achieved in adapter
settings, and subsequently consolidate previously proposed methods that
efficiently identify beneficial tasks for intermediate transfer learning. We
experiment with a diverse set of 42 intermediate and 11 target English
classification, multiple choice, question answering, and sequence tagging
tasks. Our results show that efficient embedding based methods that rely solely
on the respective datasets outperform computational expensive few-shot
fine-tuning approaches. Our best methods achieve an average Regret@3 of less
than 1% across all target tasks, demonstrating that we are able to efficiently
identify the best datasets for intermediate training.