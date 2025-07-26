---
layout: publication
title: Contrastive Code Representation Learning
authors: Paras Jain, Ajay Jain, Tianjun Zhang, Pieter Abbeel, Joseph E. Gonzalez,
  Ion Stoica
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: jain2020contrastive
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.04973'}]
tags: ["EMNLP"]
short_authors: Jain et al.
---
Recent work learns contextual representations of source code by
reconstructing tokens from their context. For downstream semantic understanding
tasks like summarizing code in English, these representations should ideally
capture program functionality. However, we show that the popular
reconstruction-based BERT model is sensitive to source code edits, even when
the edits preserve semantics. We propose ContraCode: a contrastive pre-training
task that learns code functionality, not form. ContraCode pre-trains a neural
network to identify functionally similar variants of a program among many
non-equivalent distractors. We scalably generate these variants using an
automated source-to-source compiler as a form of data augmentation. Contrastive
pre-training improves JavaScript summarization and TypeScript type inference
accuracy by 2% to 13%. We also propose a new zero-shot JavaScript code clone
detection dataset, showing that ContraCode is both more robust and semantically
meaningful. On it, we outperform RoBERTa by 39% AUROC in an adversarial setting
and up to 5% on natural code.