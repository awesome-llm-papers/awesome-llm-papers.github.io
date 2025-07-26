---
layout: publication
title: Transferable Multi-domain State Generator For Task-oriented Dialogue Systems
authors: Chien-sheng Wu, Andrea Madotto, Ehsan Hosseini-asl, Caiming Xiong, Richard
  Socher, Pascale Fung
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: wu2019transferable
citations: 409
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.08743'}]
tags: ["Few-Shot", "Training Techniques"]
short_authors: Wu et al.
---
Over-dependence on domain ontology and lack of knowledge sharing across
domains are two practical and yet less studied problems of dialogue state
tracking. Existing approaches generally fall short in tracking unknown slot
values during inference and often have difficulties in adapting to new domains.
In this paper, we propose a Transferable Dialogue State Generator (TRADE) that
generates dialogue states from utterances using a copy mechanism, facilitating
knowledge transfer when predicting (domain, slot, value) triplets not
encountered during training. Our model is composed of an utterance encoder, a
slot gate, and a state generator, which are shared across domains. Empirical
results demonstrate that TRADE achieves state-of-the-art joint goal accuracy of
48.62% for the five domains of MultiWOZ, a human-human dialogue dataset. In
addition, we show its transferring ability by simulating zero-shot and few-shot
dialogue state tracking for unseen domains. TRADE achieves 60.58% joint goal
accuracy in one of the zero-shot domains, and is able to adapt to few-shot
cases without forgetting already trained domains.