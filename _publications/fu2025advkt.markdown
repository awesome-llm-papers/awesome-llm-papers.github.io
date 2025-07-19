---
layout: publication
title: 'Advkt: An Adversarial Multi-step Training Framework For Knowledge Tracing'
authors: Fu et al.
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2025
bibkey: fu2025advkt
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.04706'}]
tags: [RAG, Training Techniques, Tools, Reinforcement Learning, Security, Datasets]
---
Knowledge Tracing (KT) monitors students' knowledge states and simulates
their responses to question sequences. Existing KT models typically follow a
single-step training paradigm, which leads to discrepancies with the multi-step
inference process required in real-world simulations, resulting in significant
error accumulation. This accumulation of error, coupled with the issue of data
sparsity, can substantially degrade the performance of recommendation models in
the intelligent tutoring systems. To address these challenges, we propose a
novel Adversarial Multi-Step Training Framework for Knowledge Tracing (AdvKT),
which, for the first time, focuses on the multi-step KT task. More
specifically, AdvKT leverages adversarial learning paradigm involving a
generator and a discriminator. The generator mimics high-reward responses,
effectively reducing error accumulation across multiple steps, while the
discriminator provides feedback to generate synthetic data. Additionally, we
design specialized data augmentation techniques to enrich the training data
with realistic variations, ensuring that the model generalizes well even in
scenarios with sparse data. Experiments conducted on four real-world datasets
demonstrate the superiority of AdvKT over existing KT models, showcasing its
ability to address both error accumulation and data sparsity issues
effectively.