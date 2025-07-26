---
layout: publication
title: Query-reduction Networks For Question Answering
authors: Minjoon Seo, Sewon Min, Ali Farhadi, Hannaneh Hajishirzi
conference: Arxiv
year: 2016
bibkey: seo2016query
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.04582'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Seo et al.
---
In this paper, we study the problem of question answering when reasoning over
multiple facts is required. We propose Query-Reduction Network (QRN), a variant
of Recurrent Neural Network (RNN) that effectively handles both short-term
(local) and long-term (global) sequential dependencies to reason over multiple
facts. QRN considers the context sentences as a sequence of state-changing
triggers, and reduces the original query to a more informed query as it
observes each trigger (context sentence) through time. Our experiments show
that QRN produces the state-of-the-art results in bAbI QA and dialog tasks, and
in a real goal-oriented dialog dataset. In addition, QRN formulation allows
parallelization on RNN's time axis, saving an order of magnitude in time
complexity for training and inference.