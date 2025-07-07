---
layout: publication
title: Conversational Question Answering Over Knowledge Graphs With Transformer And
  Graph Attention Networks
authors: Endri Kacupaj et al.
conference: Arxiv
year: 2021
citations: 31
bibkey: kacupaj2021conversational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.01569'}]
tags: [RAG, Attention Mechanism, Transformer, Model Architecture]
---
This paper addresses the task of (complex) conversational question answering
over a knowledge graph. For this task, we propose LASAGNE (muLti-task semAntic
parSing with trAnsformer and Graph atteNtion nEtworks). It is the first
approach, which employs a transformer architecture extended with Graph
Attention Networks for multi-task neural semantic parsing. LASAGNE uses a
transformer model for generating the base logical forms, while the Graph
Attention model is used to exploit correlations between (entity) types and
predicates to produce node representations. LASAGNE also includes a novel
entity recognition module which detects, links, and ranks all relevant entities
in the question context. We evaluate LASAGNE on a standard dataset for complex
sequential question answering, on which it outperforms existing baseline
averages on all question types. Specifically, we show that LASAGNE improves the
F1-score on eight out of ten question types; in some cases, the increase in
F1-score is more than 20% compared to the state of the art.