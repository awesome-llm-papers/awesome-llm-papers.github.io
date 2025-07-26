---
layout: publication
title: How Many Data Points Is A Prompt Worth?
authors: Teven Le Scao, Alexander M. Rush
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: scao2021how
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.08493'}]
tags: ["NAACL", "Prompting"]
short_authors: Teven Le Scao, Alexander M. Rush
---
When fine-tuning pretrained models for classification, researchers either use
a generic model head or a task-specific prompt for prediction. Proponents of
prompting have argued that prompts provide a method for injecting task-specific
guidance, which is beneficial in low-data regimes. We aim to quantify this
benefit through rigorous testing of prompts in a fair setting: comparing
prompted and head-based fine-tuning in equal conditions across many tasks and
data sizes. By controlling for many sources of advantage, we find that
prompting does indeed provide a benefit, and that this benefit can be
quantified per task. Results show that prompting is often worth 100s of data
points on average across classification tasks.