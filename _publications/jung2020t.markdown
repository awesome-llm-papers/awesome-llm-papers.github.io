---
layout: publication
title: 'T-GAP: Learning To Walk Across Time For Temporal Knowledge Graph Completion'
authors: Jung Jaehun, Jung Jinhong, Kang U
conference: Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery &amp;
  Data Mining
year: 2020
bibkey: jung2020t
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.10595'}]
tags: [Interpretability And Explainability, Attention Mechanism, Model Architecture,
  Reinforcement Learning, KDD]
---
Temporal knowledge graphs (TKGs) inherently reflect the transient nature of
real-world knowledge, as opposed to static knowledge graphs. Naturally,
automatic TKG completion has drawn much research interests for a more realistic
modeling of relational reasoning. However, most of the existing mod-els for TKG
completion extend static KG embeddings that donot fully exploit TKG structure,
thus lacking in 1) account-ing for temporally relevant events already residing
in the lo-cal neighborhood of a query, and 2) path-based inference that
facilitates multi-hop reasoning and better interpretability. In this paper, we
propose T-GAP, a novel model for TKG completion that maximally utilizes both
temporal information and graph structure in its encoder and decoder. T-GAP
encodes query-specific substructure of TKG by focusing on the temporal
displacement between each event and the query times-tamp, and performs
path-based inference by propagating attention through the graph. Our empirical
experiments demonstrate that T-GAP not only achieves superior performance
against state-of-the-art baselines, but also competently generalizes to queries
with unseen timestamps. Through extensive qualitative analyses, we also show
that T-GAP enjoys from transparent interpretability, and follows human
intuition in its reasoning process.