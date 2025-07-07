---
layout: publication
title: Knowledge Prompting In Pre-trained Language Model For Natural Language Understanding
authors: Jianing Wang et al.
conference: Arxiv
year: 2022
citations: 15
bibkey: wang2022knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.08536'}]
tags: [Training Techniques, RAG, Attention Mechanism, Tools, Prompting, Model Architecture]
---
Knowledge-enhanced Pre-trained Language Model (PLM) has recently received
significant attention, which aims to incorporate factual knowledge into PLMs.
However, most existing methods modify the internal structures of fixed types of
PLMs by stacking complicated modules, and introduce redundant and irrelevant
factual knowledge from knowledge bases (KBs). In this paper, to address these
problems, we introduce a seminal knowledge prompting paradigm and further
propose a knowledge-prompting-based PLM framework KP-PLM. This framework can be
flexibly combined with existing mainstream PLMs. Specifically, we first
construct a knowledge sub-graph from KBs for each context. Then we design
multiple continuous prompts rules and transform the knowledge sub-graph into
natural language prompts. To further leverage the factual knowledge from these
prompts, we propose two novel knowledge-aware self-supervised tasks including
prompt relevance inspection and masked prompt modeling. Extensive experiments
on multiple natural language understanding (NLU) tasks show the superiority of
KP-PLM over other state-of-the-art methods in both full-resource and
low-resource settings.