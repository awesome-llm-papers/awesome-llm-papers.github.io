---
layout: publication
title: 'Unifiedqa: Crossing Format Boundaries With A Single QA System'
authors: Daniel Khashabi, Sewon Min, Tushar Khot, Ashish Sabharwal, Oyvind Tafjord,
  Peter Clark, Hannaneh Hajishirzi
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: khashabi2020unifiedqa
citations: 450
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00700'}]
tags: ["EMNLP"]
short_authors: Khashabi et al.
---
Question answering (QA) tasks have been posed using a variety of formats,
such as extractive span selection, multiple choice, etc. This has led to
format-specialized models, and even to an implicit division in the QA
community. We argue that such boundaries are artificial and perhaps
unnecessary, given the reasoning abilities we seek to teach are not governed by
the format. As evidence, we use the latest advances in language modeling to
build a single pre-trained QA model, UnifiedQA, that performs surprisingly well
across 17 QA datasets spanning 4 diverse formats. UnifiedQA performs on par
with 9 different models that were trained on individual datasets themselves.
Even when faced with 12 unseen datasets of observed formats, UnifiedQA performs
surprisingly well, showing strong generalization from its out-of-format
training data. Finally, simply fine-tuning this pre-trained QA model into
specialized models results in a new state of the art on 6 datasets,
establishing UnifiedQA as a strong starting point for building QA systems.