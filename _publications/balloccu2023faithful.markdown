---
layout: publication
title: Faithful Path Language Modeling For Explainable Recommendation Over Knowledge
  Graph
authors: Balloccu et al.
conference: Proceedings of the ACM Web Conference 2022
year: 2023
bibkey: balloccu2023faithful
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.16452'}]
tags: [Interpretability And Explainability, Alt, Model Architecture, Language Modeling,
  Reinforcement Learning]
---
The integration of path reasoning with language modeling in recommender
systems has shown promise for enhancing explainability but often struggles with
the authenticity of the explanations provided. Traditional models modify their
architecture to produce entities and relations alternately--for example,
employing separate heads for each in the model--which does not ensure the
authenticity of paths reflective of actual Knowledge Graph (KG) connections.
This misalignment can lead to user distrust due to the generation of corrupted
paths. Addressing this, we introduce PEARLM (Path-based Explainable-Accurate
Recommender based on Language Modelling), which innovates with a Knowledge
Graph Constraint Decoding (KGCD) mechanism. This mechanism ensures zero
incidence of corrupted paths by enforcing adherence to valid KG connections at
the decoding level, agnostic of the underlying model architecture. By
integrating direct token embedding learning from KG paths, PEARLM not only
guarantees the generation of plausible and verifiable explanations but also
highly enhances recommendation accuracy. We validate the effectiveness of our
approach through a rigorous empirical assessment, employing a newly proposed
metric that quantifies the integrity of explanation paths. Our results
demonstrate a significant improvement over existing methods, effectively
eliminating the generation of inaccurate paths and advancing the
state-of-the-art in explainable recommender systems.