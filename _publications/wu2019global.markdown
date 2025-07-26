---
layout: publication
title: Global-to-local Memory Pointer Networks For Task-oriented Dialogue
authors: Chien-sheng Wu, Richard Socher, Caiming Xiong
conference: Arxiv
year: 2019
bibkey: wu2019global
citations: 128
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.04713'}]
tags: ["Datasets", "Evaluation", "Tools"]
short_authors: Chien-sheng Wu, Richard Socher, Caiming Xiong
---
End-to-end task-oriented dialogue is challenging since knowledge bases are
usually large, dynamic and hard to incorporate into a learning framework. We
propose the global-to-local memory pointer (GLMP) networks to address this
issue. In our model, a global memory encoder and a local memory decoder are
proposed to share external knowledge. The encoder encodes dialogue history,
modifies global contextual representation, and generates a global memory
pointer. The decoder first generates a sketch response with unfilled slots.
Next, it passes the global memory pointer to filter the external knowledge for
relevant information, then instantiates the slots via the local memory
pointers. We empirically show that our model can improve copy accuracy and
mitigate the common out-of-vocabulary problem. As a result, GLMP is able to
improve over the previous state-of-the-art models in both simulated bAbI
Dialogue dataset and human-human Stanford Multi-domain Dialogue dataset on
automatic and human evaluation.