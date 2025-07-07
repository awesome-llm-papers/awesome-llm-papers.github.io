---
layout: publication
title: Fine Grained Knowledge Transfer For Personalized Task-oriented Dialogue Systems
authors: Kaixiang Mo, Yu Zhang, Qiang Yang, Pascale Fung
conference: Arxiv
year: 2017
citations: 15
bibkey: mo2017fine
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.04079'}]
tags: [Fine-Tuning, Reinforcement Learning, Agentic, Training Techniques]
---
Training a personalized dialogue system requires a lot of data, and the data
collected for a single user is usually insufficient. One common practice for
this problem is to share training dialogues between different users and train
multiple sequence-to-sequence dialogue models together with transfer learning.
However, current sequence-to-sequence transfer learning models operate on the
entire sentence, which might cause negative transfer if different personal
information from different users is mixed up. We propose a personalized decoder
model to transfer finer granularity phrase-level knowledge between different
users while keeping personal preferences of each user intact. A novel personal
control gate is introduced, enabling the personalized decoder to switch between
generating personalized phrases and shared phrases. The proposed personalized
decoder model can be easily combined with various deep models and can be
trained with reinforcement learning. Real-world experimental results
demonstrate that the phrase-level personalized decoder improves the BLEU over
multiple sentence-level transfer baseline models by as much as 7.5%.