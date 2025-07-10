---
layout: publication
title: 'On The Safety Of Conversational Models: Taxonomy, Dataset, And Benchmark'
authors: Hao Sun et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2021
citations: 15
bibkey: sun2021safety
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08466'}]
tags: [Responsible AI, Tools, Reinforcement Learning, Evaluation]
---
Dialogue safety problems severely limit the real-world deployment of neural
conversational models and have attracted great research interests recently.
However, dialogue safety problems remain under-defined and the corresponding
dataset is scarce. We propose a taxonomy for dialogue safety specifically
designed to capture unsafe behaviors in human-bot dialogue settings, with
focuses on context-sensitive unsafety, which is under-explored in prior works.
To spur research in this direction, we compile DiaSafety, a dataset with rich
context-sensitive unsafe examples. Experiments show that existing safety
guarding tools fail severely on our dataset. As a remedy, we train a dialogue
safety classifier to provide a strong baseline for context-sensitive dialogue
unsafety detection. With our classifier, we perform safety evaluations on
popular conversational models and show that existing dialogue systems still
exhibit concerning context-sensitive safety problems.