---
layout: publication
title: Language Generation With Multi-hop Reasoning On Commonsense Knowledge Graph
authors: Haozhe Ji, Pei Ke, Shaohan Huang, Furu Wei, Xiaoyan Zhu, Minlie Huang
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: ji2020language
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.11692'}]
tags: ["EMNLP"]
short_authors: Ji et al.
---
Despite the success of generative pre-trained language models on a series of
text generation tasks, they still suffer in cases where reasoning over
underlying commonsense knowledge is required during generation. Existing
approaches that integrate commonsense knowledge into generative pre-trained
language models simply transfer relational knowledge by post-training on
individual knowledge triples while ignoring rich connections within the
knowledge graph. We argue that exploiting both the structural and semantic
information of the knowledge graph facilitates commonsense-aware text
generation. In this paper, we propose Generation with Multi-Hop Reasoning Flow
(GRF) that enables pre-trained models with dynamic multi-hop reasoning on
multi-relational paths extracted from the external commonsense knowledge graph.
We empirically show that our model outperforms existing baselines on three text
generation tasks that require reasoning over commonsense knowledge. We also
demonstrate the effectiveness of the dynamic multi-hop reasoning module with
reasoning paths inferred by the model that provide rationale to the generation.