---
layout: publication
title: Weakly Supervised Temporal Adjacent Network For Language Grounding
authors: Wang et al.
conference: IEEE Transactions on Multimedia
year: 2021
bibkey: wang2021weakly
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.16136'}]
tags: [RAG, Training Techniques, Tools, Evaluation, Multimodal Models, Datasets]
---
Temporal language grounding (TLG) is a fundamental and challenging problem
for vision and language understanding. Existing methods mainly focus on fully
supervised setting with temporal boundary labels for training, which, however,
suffers expensive cost of annotation. In this work, we are dedicated to weakly
supervised TLG, where multiple description sentences are given to an untrimmed
video without temporal boundary labels. In this task, it is critical to learn a
strong cross-modal semantic alignment between sentence semantics and visual
content. To this end, we introduce a novel weakly supervised temporal adjacent
network (WSTAN) for temporal language grounding. Specifically, WSTAN learns
cross-modal semantic alignment by exploiting temporal adjacent network in a
multiple instance learning (MIL) paradigm, with a whole description paragraph
as input. Moreover, we integrate a complementary branch into the framework,
which explicitly refines the predictions with pseudo supervision from the MIL
stage. An additional self-discriminating loss is devised on both the MIL branch
and the complementary branch, aiming to enhance semantic discrimination by
self-supervising. Extensive experiments are conducted on three widely used
benchmark datasets, *i.e.*, ActivityNet-Captions, Charades-STA, and
DiDeMo, and the results demonstrate the effectiveness of our approach.