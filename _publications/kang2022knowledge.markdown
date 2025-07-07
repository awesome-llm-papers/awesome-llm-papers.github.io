---
layout: publication
title: 'KALA: Knowledge-augmented Language Model Adaptation'
authors: Minki Kang, Jinheon Baek, Sung Ju Hwang
conference: Arxiv
year: 2022
citations: 15
bibkey: kang2022knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.10555'}, {name: Code,
    url: 'https://github.com/Nardien/KALA/'}]
tags: [Training Techniques, Pre-Training, Tools, Fine-Tuning, Has Code]
---
Pre-trained language models (PLMs) have achieved remarkable success on
various natural language understanding tasks. Simple fine-tuning of PLMs, on
the other hand, might be suboptimal for domain-specific tasks because they
cannot possibly cover knowledge from all domains. While adaptive pre-training
of PLMs can help them obtain domain-specific knowledge, it requires a large
training cost. Moreover, adaptive pre-training can harm the PLM's performance
on the downstream task by causing catastrophic forgetting of its general
knowledge. To overcome such limitations of adaptive pre-training for PLM
adaption, we propose a novel domain adaption framework for PLMs coined as
Knowledge-Augmented Language model Adaptation (KALA), which modulates the
intermediate hidden representations of PLMs with domain knowledge, consisting
of entities and their relational facts. We validate the performance of our KALA
on question answering and named entity recognition tasks on multiple datasets
across various domains. The results show that, despite being computationally
efficient, our KALA largely outperforms adaptive pre-training. Code is
available at: https://github.com/Nardien/KALA/.