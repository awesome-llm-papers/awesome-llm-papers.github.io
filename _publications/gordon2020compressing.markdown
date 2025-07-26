---
layout: publication
title: 'Compressing BERT: Studying The Effects Of Weight Pruning On Transfer Learning'
authors: Mitchell A. Gordon, Kevin Duh, Nicholas Andrews
conference: Proceedings of the 5th Workshop on Representation Learning for NLP
year: 2020
bibkey: gordon2020compressing
citations: 233
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.08307'}]
tags: ["Efficiency", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Mitchell A. Gordon, Kevin Duh, Nicholas Andrews
---
Pre-trained universal feature extractors, such as BERT for natural language
processing and VGG for computer vision, have become effective methods for
improving deep learning models without requiring more labeled data. While
effective, feature extractors like BERT may be prohibitively large for some
deployment scenarios. We explore weight pruning for BERT and ask: how does
compression during pre-training affect transfer learning? We find that pruning
affects transfer learning in three broad regimes. Low levels of pruning
(30-40%) do not affect pre-training loss or transfer to downstream tasks at
all. Medium levels of pruning increase the pre-training loss and prevent useful
pre-training information from being transferred to downstream tasks. High
levels of pruning additionally prevent models from fitting downstream datasets,
leading to further degradation. Finally, we observe that fine-tuning BERT on a
specific task does not improve its prunability. We conclude that BERT can be
pruned once during pre-training rather than separately for each task without
affecting performance.