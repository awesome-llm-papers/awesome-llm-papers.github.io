---
layout: publication
title: 'Probing The Probing Paradigm: Does Probing Accuracy Entail Task Relevance?'
authors: Abhilasha Ravichander, Yonatan Belinkov, Eduard Hovy
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: ravichander2020probing
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00719'}]
tags: ["EACL"]
short_authors: Abhilasha Ravichander, Yonatan Belinkov, Eduard Hovy
---
Although neural models have achieved impressive results on several NLP
benchmarks, little is understood about the mechanisms they use to perform
language tasks. Thus, much recent attention has been devoted to analyzing the
sentence representations learned by neural encoders, through the lens of
`probing' tasks. However, to what extent was the information encoded in
sentence representations, as discovered through a probe, actually used by the
model to perform its task? In this work, we examine this probing paradigm
through a case study in Natural Language Inference, showing that models can
learn to encode linguistic properties even if they are not needed for the task
on which the model was trained. We further identify that pretrained word
embeddings play a considerable role in encoding these properties rather than
the training task itself, highlighting the importance of careful controls when
designing probing experiments. Finally, through a set of controlled synthetic
tasks, we demonstrate models can encode these properties considerably above
chance-level even when distributed in the data as random noise, calling into
question the interpretation of absolute claims on probing tasks.