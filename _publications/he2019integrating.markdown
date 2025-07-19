---
layout: publication
title: Integrating Graph Contextualized Knowledge Into Pre-trained Language Models
authors: He et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2019
bibkey: he2019integrating
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.00147'}]
tags: [Model Architecture, Training Techniques, ACL, EMNLP, Transformer, Reinforcement
    Learning]
---
Complex node interactions are common in knowledge graphs, and these
interactions also contain rich knowledge information. However, traditional
methods usually treat a triple as a training unit during the knowledge
representation learning (KRL) procedure, neglecting contextualized information
of the nodes in knowledge graphs (KGs). We generalize the modeling object to a
very general form, which theoretically supports any subgraph extracted from the
knowledge graph, and these subgraphs are fed into a novel transformer-based
model to learn the knowledge embeddings. To broaden usage scenarios of
knowledge, pre-trained language models are utilized to build a model that
incorporates the learned knowledge representations. Experimental results
demonstrate that our model achieves the state-of-the-art performance on several
medical NLP tasks, and improvement above TransE indicates that our KRL method
captures the graph contextualized information effectively.