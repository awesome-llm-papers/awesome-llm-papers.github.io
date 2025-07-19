---
layout: publication
title: A Prompting-based Representation Learning Method For Recommendation With Large
  Language Models
authors: Chen Junyi, Suzumura Toyotaro
conference: Proceedings of the ACM Web Conference 2024
year: 2024
bibkey: chen2024prompting
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.16674'}]
tags: [RAG, GPT, Prompting, Tools, Evaluation, BERT, Model Architecture]
---
In recent years, Recommender Systems (RS) have witnessed a transformative
shift with the advent of Large Language Models (LLMs) in the field of Natural
Language Processing (NLP). Models such as GPT-3.5/4, Llama, have demonstrated
unprecedented capabilities in understanding and generating human-like text. The
extensive information pre-trained by these LLMs allows for the potential to
capture a more profound semantic representation from different contextual
information of users and items.
  While the great potential lies behind the thriving of LLMs, the challenge of
leveraging user-item preferences from contextual information and its alignment
with the improvement of Recommender Systems needs to be addressed. Believing
that a better understanding of the user or item itself can be the key factor in
improving recommendation performance, we conduct research on generating
informative profiles using state-of-the-art LLMs.
  To boost the linguistic abilities of LLMs in Recommender Systems, we
introduce the Prompting-Based Representation Learning Method for Recommendation
(P4R). In our P4R framework, we utilize the LLM prompting strategy to create
personalized item profiles. These profiles are then transformed into semantic
representation spaces using a pre-trained BERT model for text embedding.
Furthermore, we incorporate a Graph Convolution Network (GCN) for collaborative
filtering representation. The P4R framework aligns these two embedding spaces
in order to address the general recommendation tasks. In our evaluation, we
compare P4R with state-of-the-art Recommender models and assess the quality of
prompt-based profile generation.