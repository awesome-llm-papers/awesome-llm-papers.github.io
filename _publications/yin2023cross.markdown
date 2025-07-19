---
layout: publication
title: Cross-modal Reasoning With Event Correlation For Video Question Answering
authors: Yin et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2023
bibkey: yin2023cross
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.12721'}]
tags: [Model Architecture, Merging, Evaluation, LLM for Code, Transformer, Multimodal
    Models, Datasets, Attention Mechanism, Alt]
---
Video Question Answering (VideoQA) is a very attractive and challenging
research direction aiming to understand complex semantics of heterogeneous data
from two domains, i.e., the spatio-temporal video content and the word sequence
in question. Although various attention mechanisms have been utilized to manage
contextualized representations by modeling intra- and inter-modal relationships
of the two modalities, one limitation of the predominant VideoQA methods is the
lack of reasoning with event correlation, that is, sensing and analyzing
relationships among abundant and informative events contained in the video. In
this paper, we introduce the dense caption modality as a new auxiliary and
distill event-correlated information from it to infer the correct answer. To
this end, we propose a novel end-to-end trainable model, Event-Correlated Graph
Neural Networks (EC-GNNs), to perform cross-modal reasoning over information
from the three modalities (i.e., caption, video, and question). Besides the
exploitation of a brand new modality, we employ cross-modal reasoning modules
for explicitly modeling inter-modal relationships and aggregating relevant
information across different modalities, and we propose a question-guided
self-adaptive multi-modal fusion module to collect the question-oriented and
event-correlated evidence through multi-step reasoning. We evaluate our model
on two widely-used benchmark datasets and conduct an ablation study to justify
the effectiveness of each proposed component.