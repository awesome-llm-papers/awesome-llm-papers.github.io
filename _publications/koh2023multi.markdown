---
layout: publication
title: 'Multi-view Zero-shot Open Intent Induction From Dialogues: Multi Domain Batch
  And Proxy Gradient Transfer'
authors: Koh et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2023
bibkey: koh2023multi
citations: 390
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13099'}]
tags: [Model Architecture, BERT, LLM for Code, Datasets, Reinforcement Learning]
---
In Task Oriented Dialogue (TOD) system, detecting and inducing new intents
are two main challenges to apply the system in the real world. In this paper,
we suggest the semantic multi-view model to resolve these two challenges: (1)
SBERT for General Embedding (GE), (2) Multi Domain Batch (MDB) for dialogue
domain knowledge, and (3) Proxy Gradient Transfer (PGT) for cluster-specialized
semantic. MDB feeds diverse dialogue datasets to the model at once to tackle
the multi-domain problem by learning the multiple domain knowledge. We
introduce a novel method PGT, which employs the Siamese network to fine-tune
the model with a clustering method directly.Our model can learn how to cluster
dialogue utterances by using PGT. Experimental results demonstrate that our
multi-view model with MDB and PGT significantly improves the Open Intent
Induction performance compared to baseline systems.