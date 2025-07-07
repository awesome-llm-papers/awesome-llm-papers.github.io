---
layout: publication
title: 'ECONET: Effective Continual Pretraining Of Language Models For Event Temporal
  Reasoning'
authors: Rujun Han, Xiang Ren, Nanyun Peng
conference: Arxiv
year: 2020
citations: 21
bibkey: han2020effective
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15283'}]
tags: [Training Techniques, Pre-Training, Attention Mechanism, Fine-Tuning, Tools,
  Applications, Model Architecture]
---
While pre-trained language models (PTLMs) have achieved noticeable success on
many NLP tasks, they still struggle for tasks that require event temporal
reasoning, which is essential for event-centric applications. We present a
continual pre-training approach that equips PTLMs with targeted knowledge about
event temporal relations. We design self-supervised learning objectives to
recover masked-out event and temporal indicators and to discriminate sentences
from their corrupted counterparts (where event or temporal indicators got
replaced). By further pre-training a PTLM with these objectives jointly, we
reinforce its attention to event and temporal information, yielding enhanced
capability on event temporal reasoning. This effective continual pre-training
framework for event temporal reasoning (ECONET) improves the PTLMs' fine-tuning
performances across five relation extraction and question answering tasks and
achieves new or on-par state-of-the-art performances in most of our downstream
tasks.