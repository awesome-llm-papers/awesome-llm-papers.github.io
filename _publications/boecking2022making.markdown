---
layout: publication
title: Making The Most Of Text Semantics To Improve Biomedical Vision--language Processing
authors: Boecking et al.
conference: Lecture Notes in Computer Science
year: 2022
bibkey: boecking2022making
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.09817'}]
tags: [Datasets, RAG, Evaluation, Training Techniques]
---
Multi-modal data abounds in biomedicine, such as radiology images and
reports. Interpreting this data at scale is essential for improving clinical
care and accelerating clinical research. Biomedical text with its complex
semantics poses additional challenges in vision--language modelling compared to
the general domain, and previous work has used insufficiently adapted models
that lack domain-specific language understanding. In this paper, we show that
principled textual semantic modelling can substantially improve contrastive
learning in self-supervised vision--language processing. We release a language
model that achieves state-of-the-art results in radiology natural language
inference through its improved vocabulary and novel language pretraining
objective leveraging semantics and discourse characteristics in radiology
reports. Further, we propose a self-supervised joint vision--language approach
with a focus on better text modelling. It establishes new state of the art
results on a wide range of publicly available benchmarks, in part by leveraging
our new domain-specific language model. We release a new dataset with
locally-aligned phrase grounding annotations by radiologists to facilitate the
study of complex semantic modelling in biomedical vision--language processing.
A broad evaluation, including on this new dataset, shows that our contrastive
learning approach, aided by textual-semantic modelling, outperforms prior
methods in segmentation tasks, despite only using a global-alignment objective.