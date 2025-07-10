---
layout: publication
title: 'Unipelt: A Unified Framework For Parameter-efficient Language Model Tuning'
authors: Yuning Mao et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2021
citations: 42
bibkey: mao2021unified
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.07577'}]
tags: [Tools, Training Techniques, Fine-Tuning, Evaluation]
---
Recent parameter-efficient language model tuning (PELT) methods manage to
match the performance of fine-tuning with much fewer trainable parameters and
perform especially well when training data is limited. However, different PELT
methods may perform rather differently on the same task, making it nontrivial
to select the most appropriate method for a specific task, especially
considering the fast-growing number of new PELT methods and tasks. In light of
model diversity and the difficulty of model selection, we propose a unified
framework, UniPELT, which incorporates different PELT methods as submodules and
learns to activate the ones that best suit the current data or task setup via
gating mechanism. On the GLUE benchmark, UniPELT consistently achieves 1~4%
gains compared to the best individual PELT method that it incorporates and even
outperforms fine-tuning under different setups. Moreover, UniPELT generally
surpasses the upper bound that takes the best performance of all its submodules
used individually on each task, indicating that a mixture of multiple PELT
methods may be inherently more effective than single methods.