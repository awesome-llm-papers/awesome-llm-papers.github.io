---
layout: publication
title: Large Language Models Are Few-shot Clinical Information Extractors
authors: Monica Agrawal, Stefan Hegselmann, Hunter Lang, Yoon Kim, David Sontag
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: agrawal2022large
citations: 191
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12689'}]
tags: ["EMNLP", "Few-Shot"]
short_authors: Agrawal et al.
---
A long-running goal of the clinical NLP community is the extraction of
important variables trapped in clinical notes. However, roadblocks have
included dataset shift from the general domain and a lack of public clinical
corpora and annotations. In this work, we show that large language models, such
as InstructGPT, perform well at zero- and few-shot information extraction from
clinical text despite not being trained specifically for the clinical domain.
Whereas text classification and generation performance have already been
studied extensively in such models, here we additionally demonstrate how to
leverage them to tackle a diverse set of NLP tasks which require more
structured outputs, including span identification, token-level sequence
classification, and relation extraction. Further, due to the dearth of
available data to evaluate these systems, we introduce new datasets for
benchmarking few-shot clinical information extraction based on a manual
re-annotation of the CASI dataset for new tasks. On the clinical extraction
tasks we studied, the GPT-3 systems significantly outperform existing zero- and
few-shot baselines.