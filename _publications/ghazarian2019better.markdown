---
layout: publication
title: Better Automatic Evaluation Of Open-domain Dialogue Systems With Contextualized
  Embeddings
authors: Sarik Ghazarian, Johnny Tian-zheng Wei, Aram Galstyan, Nanyun Peng
conference: Proceedings of the Workshop on Methods for Optimizing and Evaluating Neural
  Language Generation
year: 2019
bibkey: ghazarian2019better
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.10635'}]
tags: ["Evaluation"]
short_authors: Ghazarian et al.
---
Despite advances in open-domain dialogue systems, automatic evaluation of
such systems is still a challenging problem. Traditional reference-based
metrics such as BLEU are ineffective because there could be many valid
responses for a given context that share no common words with reference
responses. A recent work proposed Referenced metric and Unreferenced metric
Blended Evaluation Routine (RUBER) to combine a learning-based metric, which
predicts relatedness between a generated response and a given query, with
reference-based metric; it showed high correlation with human judgments. In
this paper, we explore using contextualized word embeddings to compute more
accurate relatedness scores, thus better evaluation metrics. Experiments show
that our evaluation metrics outperform RUBER, which is trained on static
embeddings.