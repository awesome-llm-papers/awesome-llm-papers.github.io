---
layout: publication
title: 'Rewarding Smatch: Transition-based AMR Parsing With Reinforcement Learning'
authors: Naseem et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: naseem2019rewarding
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.13370'}]
tags: [Model Architecture, Training Techniques, ACL, Agentic, Transformer, Reinforcement
    Learning, Attention Mechanism]
---
Our work involves enriching the Stack-LSTM transition-based AMR parser
(Ballesteros and Al-Onaizan, 2017) by augmenting training with Policy Learning
and rewarding the Smatch score of sampled graphs. In addition, we also combined
several AMR-to-text alignments with an attention mechanism and we supplemented
the parser with pre-processed concept identification, named entities and
contextualized embeddings. We achieve a highly competitive performance that is
comparable to the best published results. We show an in-depth study ablating
each of the new components of the parser