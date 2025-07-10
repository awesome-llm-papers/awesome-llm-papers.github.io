---
layout: publication
title: 'RASAT: Integrating Relational Structures Into Pretrained Seq2seq Model For
  Text-to-sql'
authors: Jiexing Qi et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
citations: 31
bibkey: qi2022integrating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.06983'}]
tags: [Model Architecture, Attention Mechanism, Transformer, RAG, Evaluation]
---
Relational structures such as schema linking and schema encoding have been
validated as a key component to qualitatively translating natural language into
SQL queries. However, introducing these structural relations comes with prices:
they often result in a specialized model structure, which largely prohibits
using large pretrained models in text-to-SQL. To address this problem, we
propose RASAT: a Transformer seq2seq architecture augmented with relation-aware
self-attention that could leverage a variety of relational structures while
inheriting the pretrained parameters from the T5 model effectively. Our model
can incorporate almost all types of existing relations in the literature, and
in addition, we propose introducing co-reference relations for the multi-turn
scenario. Experimental results on three widely used text-to-SQL datasets,
covering both single-turn and multi-turn scenarios, have shown that RASAT could
achieve state-of-the-art results across all three benchmarks (75.5% EX on
Spider, 52.6% IEX on SParC, and 37.4% IEX on CoSQL).