---
layout: publication
title: Invariant Grounding For Video Question Answering
authors: Yicong Li, Xiang Wang, Junbin Xiao, Wei Ji, Tat-seng Chua
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: li2022invariant
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.02349'}]
tags: ["CVPR"]
short_authors: Li et al.
---
Video Question Answering (VideoQA) is the task of answering questions about a
video. At its core is understanding the alignments between visual scenes in
video and linguistic semantics in question to yield the answer. In leading
VideoQA models, the typical learning objective, empirical risk minimization
(ERM), latches on superficial correlations between video-question pairs and
answers as the alignments. However, ERM can be problematic, because it tends to
over-exploit the spurious correlations between question-irrelevant scenes and
answers, instead of inspecting the causal effect of question-critical scenes.
As a result, the VideoQA models suffer from unreliable reasoning. In this work,
we first take a causal look at VideoQA and argue that invariant grounding is
the key to ruling out the spurious correlations. Towards this end, we propose a
new learning framework, Invariant Grounding for VideoQA (IGV), to ground the
question-critical scene, whose causal relations with answers are invariant
across different interventions on the complement. With IGV, the VideoQA models
are forced to shield the answering process from the negative influence of
spurious correlations, which significantly improves the reasoning ability.
Experiments on three benchmark datasets validate the superiority of IGV in
terms of accuracy, visual explainability, and generalization ability over the
leading baselines.