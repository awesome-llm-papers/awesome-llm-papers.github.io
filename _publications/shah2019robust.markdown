---
layout: publication
title: Robust Zero-shot Cross-domain Slot Filling With Example Values
authors: Darsh J Shah, Raghav Gupta, Amir A Fayazi, Dilek Hakkani-tur
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: shah2019robust
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.06870'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Shah et al.
---
Task-oriented dialog systems increasingly rely on deep learning-based slot
filling models, usually needing extensive labeled training data for target
domains. Often, however, little to no target domain training data may be
available, or the training and target domain schemas may be misaligned, as is
common for web forms on similar websites. Prior zero-shot slot filling models
use slot descriptions to learn concepts, but are not robust to misaligned
schemas. We propose utilizing both the slot description and a small number of
examples of slot values, which may be easily available, to learn semantic
representations of slots which are transferable across domains and robust to
misaligned schemas. Our approach outperforms state-of-the-art models on two
multi-domain datasets, especially in the low-data setting.