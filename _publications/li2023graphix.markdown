---
layout: publication
title: 'Graphix-t5: Mixing Pre-trained Transformers With Graph-aware Layers For Text-to-sql
  Parsing'
authors: Jinyang Li et al.
conference: Arxiv
year: 2023
citations: 29
bibkey: li2023graphix
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.07507'}]
tags: [Ethics and Bias, Attention Mechanism, Transformer, Model Architecture]
---
The task of text-to-SQL parsing, which aims at converting natural language
questions into executable SQL queries, has garnered increasing attention in
recent years, as it can assist end users in efficiently extracting vital
information from databases without the need for technical background. One of
the major challenges in text-to-SQL parsing is domain generalization, i.e., how
to generalize well to unseen databases. Recently, the pre-trained text-to-text
transformer model, namely T5, though not specialized for text-to-SQL parsing,
has achieved state-of-the-art performance on standard benchmarks targeting
domain generalization. In this work, we explore ways to further augment the
pre-trained T5 model with specialized components for text-to-SQL parsing. Such
components are expected to introduce structural inductive bias into text-to-SQL
parsers thus improving model's capacity on (potentially multi-hop) reasoning,
which is critical for generating structure-rich SQLs. To this end, we propose a
new architecture GRAPHIX-T5, a mixed model with the standard pre-trained
transformer model augmented by some specially-designed graph-aware layers.
Extensive experiments and analysis demonstrate the effectiveness of GRAPHIX-T5
across four text-to-SQL benchmarks: SPIDER, SYN, REALISTIC and DK. GRAPHIX-T5
surpass all other T5-based parsers with a significant margin, achieving new
state-of-the-art performance. Notably, GRAPHIX-T5-large reach performance
superior to the original T5-large by 5.7% on exact match (EM) accuracy and 6.6%
on execution accuracy (EX). This even outperforms the T5-3B by 1.2% on EM and
1.5% on EX.