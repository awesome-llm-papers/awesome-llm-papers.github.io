---
layout: publication
title: 'JAKET: Joint Pre-training Of Knowledge Graph And Language Understanding'
authors: Yu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: yu2020jaket
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.00796'}]
tags: [RAG, Training Techniques, Tools, Language Modeling, Reinforcement Learning,
  AAAI]
---
Knowledge graphs (KGs) contain rich information about world knowledge,
entities and relations. Thus, they can be great supplements to existing
pre-trained language models. However, it remains a challenge to efficiently
integrate information from KG into language modeling. And the understanding of
a knowledge graph requires related context. We propose a novel joint
pre-training framework, JAKET, to model both the knowledge graph and language.
The knowledge module and language module provide essential information to
mutually assist each other: the knowledge module produces embeddings for
entities in text while the language module generates context-aware initial
embeddings for entities and relations in the graph. Our design enables the
pre-trained model to easily adapt to unseen knowledge graphs in new domains.
Experimental results on several knowledge-aware NLP tasks show that our
proposed framework achieves superior performance by effectively leveraging
knowledge in language understanding.