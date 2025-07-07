---
layout: publication
title: Empowering Language Models With Knowledge Graph Reasoning For Question Answering
authors: Ziniu Hu et al.
conference: Arxiv
year: 2022
citations: 18
bibkey: hu2022empowering
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.08380'}]
tags: [Reinforcement Learning, Transformer, Model Architecture, BERT]
---
Answering open-domain questions requires world knowledge about in-context
entities. As pre-trained Language Models (LMs) lack the power to store all
required knowledge, external knowledge sources, such as knowledge graphs, are
often used to augment LMs. In this work, we propose knOwledge REasOning
empowered Language Model (OREO-LM), which consists of a novel Knowledge
Interaction Layer that can be flexibly plugged into existing Transformer-based
LMs to interact with a differentiable Knowledge Graph Reasoning module
collaboratively. In this way, LM guides KG to walk towards the desired answer,
while the retrieved knowledge improves LM. By adopting OREO-LM to RoBERTa and
T5, we show significant performance gain, achieving state-of-art results in the
Closed-Book setting. The performance enhancement is mainly from the KG
reasoning's capacity to infer missing relational facts. In addition, OREO-LM
provides reasoning paths as rationales to interpret the model's decision.