---
layout: publication
title: Multimodal Dual Attention Memory For Video Story Question Answering
authors: Kim et al.
conference: Lecture Notes in Computer Science
year: 2018
bibkey: kim2018multimodal
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.07999'}]
tags: [Attention Mechanism, Transformer, Model Architecture, Multimodal Models, Datasets,
  Merging]
---
We propose a video story question-answering (QA) architecture, Multimodal
Dual Attention Memory (MDAM). The key idea is to use a dual attention mechanism
with late fusion. MDAM uses self-attention to learn the latent concepts in
scene frames and captions. Given a question, MDAM uses the second attention
over these latent concepts. Multimodal fusion is performed after the dual
attention processes (late fusion). Using this processing pipeline, MDAM learns
to infer a high-level vision-language joint representation from an abstraction
of the full video content. We evaluate MDAM on PororoQA and MovieQA datasets
which have large-scale QA annotations on cartoon videos and movies,
respectively. For both datasets, MDAM achieves new state-of-the-art results
with significant margins compared to the runner-up models. We confirm the best
performance of the dual attention mechanism combined with late fusion by
ablation studies. We also perform qualitative analysis by visualizing the
inference mechanisms of MDAM.