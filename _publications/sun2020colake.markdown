---
layout: publication
title: 'Colake: Contextualized Language And Knowledge Embedding'
authors: Tianxiang Sun, Yunfan Shao, Xipeng Qiu, Qipeng Guo, Yaru Hu, Xuanjing Huang,
  Zheng Zhang
conference: Proceedings of the 28th International Conference on Computational Linguistics
year: 2020
bibkey: sun2020colake
citations: 141
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.00309'}]
tags: ["COLING", "Model Architecture"]
short_authors: Sun et al.
---
With the emerging branch of incorporating factual knowledge into pre-trained
language models such as BERT, most existing models consider shallow, static,
and separately pre-trained entity embeddings, which limits the performance
gains of these models. Few works explore the potential of deep contextualized
knowledge representation when injecting knowledge. In this paper, we propose
the Contextualized Language and Knowledge Embedding (CoLAKE), which jointly
learns contextualized representation for both language and knowledge with the
extended MLM objective. Instead of injecting only entity embeddings, CoLAKE
extracts the knowledge context of an entity from large-scale knowledge bases.
To handle the heterogeneity of knowledge context and language context, we
integrate them in a unified data structure, word-knowledge graph (WK graph).
CoLAKE is pre-trained on large-scale WK graphs with the modified Transformer
encoder. We conduct experiments on knowledge-driven tasks, knowledge probing
tasks, and language understanding tasks. Experimental results show that CoLAKE
outperforms previous counterparts on most of the tasks. Besides, CoLAKE
achieves surprisingly high performance on our synthetic task called
word-knowledge graph completion, which shows the superiority of simultaneously
contextualizing language and knowledge representation.