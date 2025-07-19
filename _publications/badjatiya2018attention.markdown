---
layout: publication
title: Attention-based Neural Text Segmentation
authors: Badjatiya et al.
conference: Lecture Notes in Computer Science
year: 2018
bibkey: badjatiya2018attention
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.09935'}]
tags: [Datasets, Model Architecture, Evaluation, Attention Mechanism]
---
Text segmentation plays an important role in various Natural Language
Processing (NLP) tasks like summarization, context understanding, document
indexing and document noise removal. Previous methods for this task require
manual feature engineering, huge memory requirements and large execution times.
To the best of our knowledge, this paper is the first one to present a novel
supervised neural approach for text segmentation. Specifically, we propose an
attention-based bidirectional LSTM model where sentence embeddings are learned
using CNNs and the segments are predicted based on contextual information. This
model can automatically handle variable sized context information. Compared to
the existing competitive baselines, the proposed model shows a performance
improvement of ~7% in WinDiff score on three benchmark datasets.