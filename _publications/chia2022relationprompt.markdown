---
layout: publication
title: 'Relationprompt: Leveraging Prompts To Generate Synthetic Data For Zero-shot
  Relation Triplet Extraction'
authors: Yew Ken Chia, Lidong Bing, Soujanya Poria, Luo Si
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2022
bibkey: chia2022relationprompt
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.09101'}]
tags: ["Datasets", "Prompting"]
short_authors: Chia et al.
---
Despite the importance of relation extraction in building and representing
knowledge, less research is focused on generalizing to unseen relations types.
We introduce the task setting of Zero-Shot Relation Triplet Extraction
(ZeroRTE) to encourage further research in low-resource relation extraction
methods. Given an input sentence, each extracted triplet consists of the head
entity, relation label, and tail entity where the relation label is not seen at
the training stage. To solve ZeroRTE, we propose to synthesize relation
examples by prompting language models to generate structured texts. Concretely,
we unify language model prompts and structured text approaches to design a
structured prompt template for generating synthetic relation samples when
conditioning on relation label prompts (RelationPrompt). To overcome the
limitation for extracting multiple relation triplets in a sentence, we design a
novel Triplet Search Decoding method. Experiments on FewRel and Wiki-ZSL
datasets show the efficacy of RelationPrompt for the ZeroRTE task and zero-shot
relation classification. Our code and data are available at
github.com/declare-lab/RelationPrompt.