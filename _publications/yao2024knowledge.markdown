---
layout: publication
title: Knowledge Circuits In Pretrained Transformers
authors: Yao et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: yao2024knowledge
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.17969'}]
tags: [Model Architecture, ACL, In Context Learning, Transformer, GPT, Reinforcement
    Learning, Attention Mechanism]
---
The remarkable capabilities of modern large language models are rooted in
their vast repositories of knowledge encoded within their parameters, enabling
them to perceive the world and engage in reasoning. The inner workings of how
these models store knowledge have long been a subject of intense interest and
investigation among researchers. To date, most studies have concentrated on
isolated components within these models, such as the Multilayer Perceptrons and
attention head. In this paper, we delve into the computation graph of the
language model to uncover the knowledge circuits that are instrumental in
articulating specific knowledge. The experiments, conducted with GPT2 and
TinyLLAMA, have allowed us to observe how certain information heads, relation
heads, and Multilayer Perceptrons collaboratively encode knowledge within the
model. Moreover, we evaluate the impact of current knowledge editing techniques
on these knowledge circuits, providing deeper insights into the functioning and
constraints of these editing methodologies. Finally, we utilize knowledge
circuits to analyze and interpret language model behaviors such as
hallucinations and in-context learning. We believe the knowledge circuits hold
potential for advancing our understanding of Transformers and guiding the
improved design of knowledge editing. Code and data are available in
https://github.com/zjunlp/KnowledgeCircuits.