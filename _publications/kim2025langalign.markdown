---
layout: publication
title: 'LANGALIGN: Enhancing Non-english Language Models Via Cross-lingual Embedding
  Alignment'
authors: Kim et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: kim2025langalign
citations: 262
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.18603'}]
tags: [Training Techniques, Attention Mechanism, Model Architecture, Fine Tuning,
  Datasets]
---
While Large Language Models have gained attention, many service developers
still rely on embedding-based models due to practical constraints. In such
cases, the quality of fine-tuning data directly impacts performance, and
English datasets are often used as seed data for training non-English models.
In this study, we propose LANGALIGN, which enhances target language processing
by aligning English embedding vectors with those of the target language at the
interface between the language model and the task header. Experiments on
Korean, Japanese, and Chinese demonstrate that LANGALIGN significantly improves
performance across all three languages. Additionally, we show that LANGALIGN
can be applied in reverse to convert target language data into a format that an
English-based model can process.