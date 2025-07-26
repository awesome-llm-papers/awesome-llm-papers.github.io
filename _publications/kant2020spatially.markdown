---
layout: publication
title: Spatially Aware Multimodal Transformers For Textvqa
authors: Yash Kant, Dhruv Batra, Peter Anderson, Alex Schwing, Devi Parikh, Jiasen
  Lu, Harsh Agrawal
conference: Lecture Notes in Computer Science
year: 2020
bibkey: kant2020spatially
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.12146'}]
tags: ["Model Architecture"]
short_authors: Kant et al.
---
Textual cues are essential for everyday tasks like buying groceries and using
public transport. To develop this assistive technology, we study the TextVQA
task, i.e., reasoning about text in images to answer a question. Existing
approaches are limited in their use of spatial relations and rely on
fully-connected transformer-like architectures to implicitly learn the spatial
structure of a scene. In contrast, we propose a novel spatially aware
self-attention layer such that each visual entity only looks at neighboring
entities defined by a spatial graph. Further, each head in our multi-head
self-attention layer focuses on a different subset of relations. Our approach
has two advantages: (1) each head considers local context instead of dispersing
the attention amongst all visual entities; (2) we avoid learning redundant
features. We show that our model improves the absolute accuracy of current
state-of-the-art methods on TextVQA by 2.2% overall over an improved baseline,
and 4.62% on questions that involve spatial reasoning and can be answered
correctly using OCR tokens. Similarly on ST-VQA, we improve the absolute
accuracy by 4.2%. We further show that spatially aware self-attention improves
visual grounding.